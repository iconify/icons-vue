<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ix92onbve"/><path class="q7ci1nbmo"/><path class="cp8sfjr-m"/><g class="n1mjunbsu"><circle class="ucsceccrp"/><circle class="qo2cgbixy"/></g><circle class="w7ekswf6w"/><circle class="zbhb5uu-q"/><circle class="qb1e7bcto"/><circle class="n-bg1kp5o"/><path class="hgjam-k6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:girl-light-skin-tone" /></template>
<style>
.cp8sfjr-m {
  fill: var(--svg-color--ffe1bd, #ffe1bd);
  d: path("M57.3 42c6.2 0 6.2-9 0-9v-3s-35-.9-43-13c2 12.2-7.7 16-7.7 16c-6.2 0-6.2 9 0 9c0 7 7.3 18 25.3 18s25.4-11 25.4-18");
}

.hgjam-k6c {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M40.1 48.1c-5.2 3.6-11 3.6-16.2 0c-.6-.4-1.2.3-.8 1c1.6 2.6 4.8 4.9 8.9 4.9s7.3-2.3 8.9-4.9c.4-.7-.2-1.4-.8-1");
}

.ix92onbve {
  fill: var(--svg-color--594640, #594640);
  d: path("M57.8 40S61 34.4 61 26c0-11-8.1-24-29-24S3 15 3 26c0 8.4 3.1 14 3.1 14C2.5 44.1.3 52.4 3.4 57.8c1.3 2.2 14.1 10 15.3-3.9h26.4c1.3 13.8 14.1 6.1 15.3 3.9c3.2-5.4 1-13.7-2.6-17.8");
}

.n-bg1kp5o {
  cx: 19.5px;
  cy: 36.5px;
  r: 1.5px;
  fill: var(--svg-color--231f20, #231f20);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.q7ci1nbmo {
  fill: var(--svg-color--c28fef, #c28fef);
  d: path("M32 6C16.7 6 5.5 14 5.5 24C5.5 24 9.6 9 32 9s25.5 15 25.5 15C57.5 14 47.3 6 32 6");
}

.qb1e7bcto {
  cx: 19.5px;
  cy: 36.5px;
  r: 4.5px;
  fill: var(--svg-color--664e27, #664e27);
}

.qo2cgbixy {
  cx: 19.5px;
  cy: 36.5px;
  r: 6.5px;
}

.ucsceccrp {
  cx: 44.5px;
  cy: 36.5px;
  r: 6.5px;
}

.w7ekswf6w {
  cx: 44.5px;
  cy: 36.5px;
  r: 4.5px;
  fill: var(--svg-color--664e27, #664e27);
}

.zbhb5uu-q {
  cx: 44.5px;
  cy: 36.5px;
  r: 1.5px;
  fill: var(--svg-color--231f20, #231f20);
}

</style>
