Figma - https://www.figma.com/design/rwBjcajyKV4nRmlmVqbm04/Untitled?node-id=0-1&m=dev&t=EWCWuouzZmawVJVV-1

Требования: 

Бизнес-требования:

REQ_BR_01:Повышение конверсии открытых вкладов

REQ_BR_02:Оптимизация работы сотрудника банка за счет автоматизации рассчета доходности вкладов с различными параметрами

Функциональные требования:

  REQ_FR_01: В системе должна быть авторизация/аутентификация 

  REQ_FR_02: Система должна подбирать вклады по предоставленным параметрам
  
  REQ_FR_03: Система должна предоставлять статистику о ПОДОБРАННЫХ вкладах
  
  REQ_FR_04: Система должна в случае выбора вклада переводить на следующий этап “Оформление вклада”
  
  REQ_FR_05: Система должна производить КОРРЕКТНЫЙ рассчет доходности вклада с капитализацией и без
  
  REQ_FR_06: Система должна предоставлять календарь выплат для вкладов БЕЗ капитализации
  
  REQ_FR_07: Система должна позволять идентифицировать обслуживаемого клиента по паспортным данным 
  
  REQ_FR_08: Система должна позволять добавлять вклады в избранное при подборке
  
  REQ_FR_09: Система должна позволять обслужить клиента которого нет в системе банка
  
  REQ_FR_10: Система должна знакомить пользователя с интерфейсом работы 
  
  REQ_FR_11: Система должна демонстрировать дашборд сформированный на основе собранных статистических данных
  
  REQ_FR_12: Система должна позволять выгрузить статистические данные в файле формата .csv для построения индивидуальных аналитических отчетов
  

Требования к интерфейсу:

REQ_IF_01: Интерфейс должен предоставлять форму для авторизации и аутентификации пользователя.

REQ_IF_02: Интерфейс должен предоставлять форму для ввода параметров подбора вкладов.

REQ_IF_03: Интерфейс должен отображать статистику о подходящих вкладах.

REQ_IF_04: Интерфейс должен предоставлять кнопку для перехода на этап "Оформление вклада" после выбора вклада.

REQ_IF_05: Интерфейс должен отображать календарь выплат для вкладов без капитализации.

REQ_IF_06: Интерфейс должен предоставлять форму для ввода паспортных данных клиента.

REQ_IF_07: Интерфейс должен предоставлять кнопку для добавления вкладов в избранное.

REQ_IF_08: Интерфейс должен предоставлять форму для обслуживания клиента, которого нет в системе банка.

REQ_IF_09: Интерфейс должен предоставлять обучающий материал для ознакомления с интерфейсом работы.

REQ_IF_10: Интерфейс должен отображать дашборд, сформированный на основе собранных статистических данных.

REQ_IF_11: Интерфейс должен предоставлять кнопку для выгрузки статистических данных в файле формата .csv для построения индивидуальных аналитических отчетов.


Пользовательские требования:

REQ_UR_01: Я как пользователь хочу вводить параметры для подбора вкладов, чтобы найти луший вариант для клиента .

REQ_UR_02: Я как пользователь хочу просматривать статистику о подходящих вкладах, чтобы принять обоснованное решение.

REQ_UR_03: Я как пользователь хочу перейти на этап "Оформление вклада" после выбора вклада, чтобы завершить процесс открытия вклада.

REQ_UR_04: Я как пользователь хочу просматривать корректный расчет доходности вклада с капитализацией и без, чтобы предложить варианты продуктов клиенту.

REQ_UR_05: Я как пользователь хочу просматривать календарь выплат для вкладов без капитализации, чтобы помочь с планированием финансов клиента.

REQ_UR_06: Я как пользователь хочу идентифицировать клиента по паспортным данным, чтобы учитывалась его категория в банковской системе.

REQ_UR_07: Я как пользователь хочу добавлять вклады в избранное при подборке, чтобы оперативно сравнивать понравившиеся клиенту варианты.

REQ_UR_08: Я как пользователь хочу обслуживать клиента, которого нет в системе банка, чтобы привлечь его как нового клиента в банк.

REQ_UR_09: Я как пользователь хочу ознакомиться с интерфейсом работы, чтобы эффективно выполнять свою работу.

REQ_UR_10: Я как пользователь хочу просматривать дашборд, сформированный на основе собранных статистических данных, чтобы анализировать информацию.

REQ_UR_11: Я как пользователь хочу выгрузить статистические данные в файле формата .csv для построения индивидуальных аналитических отчетов, чтобы проводить более глубокий анализ.



Требования информационной безопасноти: 

REQ_IS_01: Система должна обеспечивать разграничение ролей доступа к приложению

REQ_IS_02: Система не должна хранить пароль в открытом виде в Базе данных

REQ_IS_03: В системе должнга быть аутентификация и авторизация, чтобы не допустить доступ к приложению сотрудников без разрешения на использование ПО

Нефункциональные требования:

REQ_NFR_01: Синхронный клиент серверный обмен - REST

REQ_NFR_02: Acинхронный клиент серверный обмен - RABBITMQ (при необходимости)

REQ_NFR_03: Система должны быть разработана на микросервисной архитектуре

REQ_NFR_04: Фронт часть системы должны быть разработана на React

REQ_NFR_05: Бэк системы должны быть разработан на Java Spring 3.X

REQ_NFR_06: Система должна использовать СУБД PostgreSql

План проекта:

[xoxotun_bank_plan.xls](https://github.com/user-attachments/files/17725193/xoxotun_bank_plan.xls)

Архитектура проекта:
![image](https://github.com/user-attachments/assets/b270c0c5-5bff-4d7a-b84a-9db8e1e53b54)


    <mxGraphModel dx="1868" dy="2476" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="1200" pageHeight="1920" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="588-N9UR6EX14qT44rtL-4" value="" style="group" parent="1" vertex="1" connectable="0">
          <mxGeometry x="700" y="248" width="180" height="110" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-1" value="МКС &quot;Auth&quot;" style="html=1;dropTarget=0;whiteSpace=wrap;fillColor=#dae8fc;strokeColor=#6c8ebf;" parent="588-N9UR6EX14qT44rtL-4" vertex="1">
          <mxGeometry width="180" height="90" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-2" value="" style="shape=module;jettyWidth=8;jettyHeight=4;fillColor=#fff2cc;strokeColor=#d6b656;" parent="588-N9UR6EX14qT44rtL-1" vertex="1">
          <mxGeometry x="1" width="20" height="20" relative="1" as="geometry">
            <mxPoint x="-27" y="7" as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-3" value="БД" style="html=1;whiteSpace=wrap;fillColor=#e1d5e7;strokeColor=#9673a6;" parent="588-N9UR6EX14qT44rtL-4" vertex="1">
          <mxGeometry y="90" width="180" height="20" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-5" value="" style="group" parent="1" vertex="1" connectable="0">
          <mxGeometry x="260" y="480" width="180" height="110" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-6" value="МКС &quot;Analytics&quot;" style="html=1;dropTarget=0;whiteSpace=wrap;fillColor=#dae8fc;strokeColor=#6c8ebf;" parent="588-N9UR6EX14qT44rtL-5" vertex="1">
          <mxGeometry width="180" height="90" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-7" value="" style="shape=module;jettyWidth=8;jettyHeight=4;fillColor=#fff2cc;strokeColor=#d6b656;" parent="588-N9UR6EX14qT44rtL-6" vertex="1">
          <mxGeometry x="1" width="20" height="20" relative="1" as="geometry">
            <mxPoint x="-27" y="7" as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-8" value="БД" style="html=1;whiteSpace=wrap;fillColor=#e1d5e7;strokeColor=#9673a6;" parent="588-N9UR6EX14qT44rtL-5" vertex="1">
          <mxGeometry y="90" width="180" height="20" as="geometry" />
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-14" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" parent="1" source="588-N9UR6EX14qT44rtL-31" target="588-N9UR6EX14qT44rtL-6" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-28" value="1" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];fontSize=14;labelBorderColor=default;" parent="jadxHyDA14GCOuneVWa5-14" vertex="1" connectable="0">
          <mxGeometry x="0.5081" y="-1" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-15" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" parent="1" source="588-N9UR6EX14qT44rtL-31" target="VYHcQesEsJTGwd5eS91A-1" edge="1">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="350" y="400" />
              <mxPoint x="590" y="400" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-29" value="2" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];fontSize=14;labelBorderColor=default;" parent="jadxHyDA14GCOuneVWa5-15" vertex="1" connectable="0">
          <mxGeometry x="0.7915" y="1" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-17" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;startArrow=classic;startFill=1;" parent="1" source="588-N9UR6EX14qT44rtL-31" target="588-N9UR6EX14qT44rtL-1" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-31" value="4" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];fontSize=14;labelBackgroundColor=default;labelBorderColor=default;" parent="jadxHyDA14GCOuneVWa5-17" vertex="1" connectable="0">
          <mxGeometry x="0.2496" y="1" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="3WcTQ9Did3W0srVTyYnI-1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;startArrow=classic;startFill=1;" parent="1" source="588-N9UR6EX14qT44rtL-31" target="588-N9UR6EX14qT44rtL-36" edge="1">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="350" y="400" />
              <mxPoint x="900" y="400" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="3WcTQ9Did3W0srVTyYnI-2" value="3" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];fontSize=14;labelBorderColor=default;" parent="3WcTQ9Did3W0srVTyYnI-1" vertex="1" connectable="0">
          <mxGeometry x="0.8471" y="2" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-31" value="WEB" style="rounded=1;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="290" y="277.5" width="120" height="30" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-35" value="" style="group" parent="1" vertex="1" connectable="0">
          <mxGeometry x="810" y="500" width="180" height="110" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-36" value="МКС &quot;ABS&quot;" style="html=1;dropTarget=0;whiteSpace=wrap;fillColor=#dae8fc;strokeColor=#6c8ebf;" parent="588-N9UR6EX14qT44rtL-35" vertex="1">
          <mxGeometry width="180" height="90" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-37" value="" style="shape=module;jettyWidth=8;jettyHeight=4;fillColor=#fff2cc;strokeColor=#d6b656;" parent="588-N9UR6EX14qT44rtL-36" vertex="1">
          <mxGeometry x="1" width="20" height="20" relative="1" as="geometry">
            <mxPoint x="-27" y="7" as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-38" value="БД" style="html=1;whiteSpace=wrap;fillColor=#e1d5e7;strokeColor=#9673a6;" parent="588-N9UR6EX14qT44rtL-35" vertex="1">
          <mxGeometry y="90" width="180" height="20" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-100" value="Легенда" style="rounded=0;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="790" y="15" width="360" height="35" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-101" value="Обозначение" style="rounded=0;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="790" y="50" width="120" height="25" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-102" value="описание" style="rounded=0;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="910" y="50" width="240" height="25" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-103" value="" style="rounded=0;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="790" y="75" width="120" height="25" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-104" value="Межсервисное синхроннное взаимодействие" style="rounded=0;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="910" y="75" width="240" height="25" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-105" value="" style="endArrow=classic;html=1;rounded=0;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;fillColor=#ffe6cc;strokeColor=#d79b00;" parent="1" source="588-N9UR6EX14qT44rtL-103" target="588-N9UR6EX14qT44rtL-104" edge="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="830" y="85" as="sourcePoint" />
            <mxPoint x="880" y="35" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-106" value="" style="rounded=0;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="790" y="100" width="120" height="25" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-107" value="Синхронное взаимодействие с клиентом" style="rounded=0;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="910" y="100" width="240" height="25" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-108" value="" style="endArrow=classic;html=1;rounded=0;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" parent="1" edge="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="790" y="112.29999999999995" as="sourcePoint" />
            <mxPoint x="910" y="112.29999999999995" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-125" value="&lt;font style=&quot;font-size: 14px;&quot;&gt;3&lt;/font&gt;" style="rounded=0;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="790" y="125" width="120" height="25" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-126" value="Номер информационного потока" style="rounded=0;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="910" y="125" width="240" height="25" as="geometry" />
        </mxCell>
        <mxCell id="588-N9UR6EX14qT44rtL-127" value="" style="rounded=0;whiteSpace=wrap;html=1;fillColor=none;" parent="1" vertex="1">
          <mxGeometry x="845" y="127.5" width="10" height="20" as="geometry" />
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-20" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.75;entryDx=0;entryDy=0;fillColor=#fff2cc;strokeColor=#d6b656;" parent="1" source="VYHcQesEsJTGwd5eS91A-1" target="588-N9UR6EX14qT44rtL-1" edge="1">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="640" y="316" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-34" value="7" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];fontSize=14;labelBorderColor=default;" parent="jadxHyDA14GCOuneVWa5-20" vertex="1" connectable="0">
          <mxGeometry x="-0.599" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-24" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;fillColor=#fff2cc;strokeColor=#d6b656;" parent="1" source="VYHcQesEsJTGwd5eS91A-1" target="588-N9UR6EX14qT44rtL-36" edge="1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="810" y="520" as="targetPoint" />
            <Array as="points">
              <mxPoint x="780" y="525" />
              <mxPoint x="780" y="525" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-38" value="9" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];fontSize=14;labelBorderColor=default;" parent="jadxHyDA14GCOuneVWa5-24" vertex="1" connectable="0">
          <mxGeometry x="-0.2781" y="-1" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="VYHcQesEsJTGwd5eS91A-1" value="МКС &quot;Calculator&quot;" style="html=1;dropTarget=0;whiteSpace=wrap;fillColor=#dae8fc;strokeColor=#6c8ebf;" parent="1" vertex="1">
          <mxGeometry x="500" y="480" width="180" height="90" as="geometry" />
        </mxCell>
        <mxCell id="VYHcQesEsJTGwd5eS91A-2" value="" style="shape=module;jettyWidth=8;jettyHeight=4;fillColor=#fff2cc;strokeColor=#d6b656;" parent="VYHcQesEsJTGwd5eS91A-1" vertex="1">
          <mxGeometry x="1" width="20" height="20" relative="1" as="geometry">
            <mxPoint x="-27" y="7" as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-21" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=1;exitDx=0;exitDy=0;fillColor=#fff2cc;strokeColor=#d6b656;" parent="1" source="588-N9UR6EX14qT44rtL-1" target="VYHcQesEsJTGwd5eS91A-1" edge="1">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="700" y="350" />
              <mxPoint x="670" y="350" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-35" value="8" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];fontSize=14;labelBorderColor=default;" parent="jadxHyDA14GCOuneVWa5-21" vertex="1" connectable="0">
          <mxGeometry x="0.4404" y="-2" relative="1" as="geometry">
            <mxPoint y="11" as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-22" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.75;entryDx=0;entryDy=0;fillColor=#fff2cc;strokeColor=#d6b656;" parent="1" source="588-N9UR6EX14qT44rtL-6" target="588-N9UR6EX14qT44rtL-1" edge="1">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="400" y="316" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-32" value="5" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];fontSize=14;labelBorderColor=default;" parent="jadxHyDA14GCOuneVWa5-22" vertex="1" connectable="0">
          <mxGeometry x="-0.7787" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-23" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=1;exitDx=0;exitDy=0;fillColor=#fff2cc;strokeColor=#d6b656;" parent="1" source="588-N9UR6EX14qT44rtL-1" target="588-N9UR6EX14qT44rtL-6" edge="1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="400" y="440" as="targetPoint" />
            <Array as="points">
              <mxPoint x="420" y="338" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-33" value="6" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];fontSize=14;labelBorderColor=default;" parent="jadxHyDA14GCOuneVWa5-23" vertex="1" connectable="0">
          <mxGeometry x="0.7621" y="1" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-25" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.75;entryDx=0;entryDy=0;fillColor=#fff2cc;strokeColor=#d6b656;" parent="1" source="588-N9UR6EX14qT44rtL-36" target="VYHcQesEsJTGwd5eS91A-1" edge="1">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="700" y="548" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="jadxHyDA14GCOuneVWa5-39" value="10" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];fontSize=14;labelBorderColor=default;" parent="jadxHyDA14GCOuneVWa5-25" vertex="1" connectable="0">
          <mxGeometry x="0.1601" y="1" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="SPVAMAtQ4zQ1yFRimgBC-1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;fillColor=#fff2cc;strokeColor=#d6b656;" parent="1" source="588-N9UR6EX14qT44rtL-36" target="588-N9UR6EX14qT44rtL-1" edge="1">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="1030" y="540" />
              <mxPoint x="1030" y="293" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="SPVAMAtQ4zQ1yFRimgBC-5" value="12" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];fontSize=14;labelBorderColor=default;" parent="SPVAMAtQ4zQ1yFRimgBC-1" vertex="1" connectable="0">
          <mxGeometry x="-0.1227" y="-2" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="SPVAMAtQ4zQ1yFRimgBC-3" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;fillColor=#fff2cc;strokeColor=#d6b656;" parent="1" source="588-N9UR6EX14qT44rtL-1" target="588-N9UR6EX14qT44rtL-36" edge="1">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="1010" y="320" />
              <mxPoint x="1010" y="530" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="SPVAMAtQ4zQ1yFRimgBC-4" value="11" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];fontSize=14;labelBorderColor=default;" parent="SPVAMAtQ4zQ1yFRimgBC-3" vertex="1" connectable="0">
          <mxGeometry x="0.1492" y="2" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>


