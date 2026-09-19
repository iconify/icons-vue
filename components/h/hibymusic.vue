<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="to-5kdesz"><circle class="tr2zijben"/><circle class="jx1c6ximm"/><path class="q-p5rpb0h"/><g class="atjk8mbde"><path class="bu724sb9e"/><path class="qsrm5nb_c"/></g><path class="sdx5if6ez"/></g><circle class="m-b3t7cfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hibymusic" /></template>
<style>
.atjk8mbde {
  stroke-linecap: round;
}

.bu724sb9e {
  d: path("M11.038 23.96c.015-7.891 6.424-14.277 14.316-14.263c7.892.015 14.277 6.424 14.263 14.316c-.008 7.887-6.405 14.276-14.292 14.275");
}

.jx1c6ximm {
  cx: 25.328px;
  cy: 23.997px;
  r: 2.464px;
}

.m-b3t7cfl {
  cx: 25.328px;
  cy: 23.997px;
  r: 0.75px;
  fill: currentColor;
}

.q-p5rpb0h {
  stroke-linecap: round;
  d: path("M26.194 19.543a4.54 4.54 0 0 1 3.566 3.48m-5.299 5.43a4.54 4.54 0 0 1-3.566-3.48m5.905-7.94a7.12 7.12 0 0 1 5.432 5.233m-8.377 8.698a7.12 7.12 0 0 1-5.432-5.233");
}

.qsrm5nb_c {
  d: path("M44.175 34.34c-5.712 10.41-18.78 14.217-29.19 8.505A21.5 21.5 0 0 1 4.657 29.9C1.396 18.483 8.01 6.585 19.426 3.326a21.5 21.5 0 0 1 16.45 1.939");
}

.sdx5if6ez {
  stroke-linecap: round;
  d: path("m35.874 5.264l-.004 9.087");
}

.to-5kdesz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.tr2zijben {
  cx: 25.328px;
  cy: 23.997px;
  r: 9.244px;
}

</style>
