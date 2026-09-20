<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oplpcubkc"/><path class="qu6ja6tfg"/><path class="zj2feh7er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cines-unidos" /></template>
<style>
.oplpcubkc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24M24 37.34v3.894m0-34.469v3.895m-2.648 14.17H6.824m34.352 0H26.659");
}

.qu6ja6tfg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.234 24c0 9.518-7.716 17.234-17.234 17.234S6.766 33.518 6.766 24S14.482 6.766 24 6.766S41.234 14.482 41.234 24");
}

.zj2feh7er {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.458 16.01l6.653-2.99v21.96");
}

</style>
