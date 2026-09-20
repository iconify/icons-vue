<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g0cxlq6-p"/><path class="uf8xhh57c"/><path class="c157x3par"/><path class="eik8yph1y"/><path class="j-dnsgaok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lixx" /></template>
<style>
.c157x3par {
  fill: var(--svg-color--08883e, #08883e);
  d: path("M9.462 7.615c.323.028 1.043.346 1.384 1.385c-.212-.134-1.172-.222-1.384-1.385m3.692 0c-.323.028-1.043.346-1.385 1.385c.213-.134 1.172-.222 1.385-1.385");
}

.eik8yph1y {
  fill: var(--svg-color--e47a04, #e47a04);
  d: path("M4.846 9H3v8.77h6v-1.847H4.846zm4.87 2.94l-.218-.67a.73.73 0 0 1 .079-.622c.217-.351.49-.799.65-1.076a.235.235 0 0 1 .278-.097c.346.111.692.167.802.18c.107-.013.457-.069.799-.184c.106-.033.23.009.277.101l.425.693l-1.45.277l1.777.346a.7.7 0 0 1-.018.383l-.905 2.787l-1.168.231l1.03.194l-.767 2.363l-1.361-4.195l1.73-.332z");
}

.ft5dv1b6b {
  fill: none;
}

.g0cxlq6-p {
  fill: var(--svg-color--08883e, #08883e);
  d: path("m10.846 7.838l.461-1.607l.462 1.607L11.307 9z");
}

.j-dnsgaok {
  fill: var(--svg-color--b3b3b3, #b3b3b3);
  d: path("m9.462 17.539l1.846-.231l1.846.23l-1.846.231z");
}

.uf8xhh57c {
  fill: var(--svg-color--e47a04, #e47a04);
  d: path("M21 9h-1.897l-1.795 2.866L15.512 9h-1.896l2.741 4.385l-2.741 4.384h1.896l1.796-2.866l1.795 2.866H21l-2.741-4.384z");
}

</style>
