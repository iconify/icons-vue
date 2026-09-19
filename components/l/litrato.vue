<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="sqrvcr4hm"/><path class="g560cchjq"/><path class="aptvcib5y"/><circle class="gl778ez2o"/><path class="iy7qiejzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:litrato" /></template>
<style>
.aptvcib5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.253 14.964h6.969v3.484h-6.969zm-3.131 10.348h-7.46m2.263 4.006l-3.634-6.381m-2.323 3.976l3.694-6.351m-4.71 0h7.453m-2.411-4.212l3.782 6.587m2.38-4.043l-3.75 6.418m8.844 14.2h9.25m-39 0h27.75");
}

.g560cchjq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.438 12.07V7.488h9.207v4.577m14.257 20.18v-18.78c0-.768-.866-1.39-1.934-1.39H7.116c-1.068 0-1.934.622-1.934 1.39v18.78c0 .767.866 1.39 1.934 1.39h33.852c1.068 0 1.934-.623 1.934-1.39");
}

.gl778ez2o {
  cx: 33.251px;
  cy: 39.512px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iy7qiejzg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.182 13.94V9.375h5.505v2.621");
}

.sqrvcr4hm {
  cx: 24.042px;
  cy: 22.855px;
  r: 6.638px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
