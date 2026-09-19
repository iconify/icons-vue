<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9243rqda"/><path class="sa70z1ivg"/><path class="hcav2vhso"/><ellipse class="vd3fi28uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:everydollar" /></template>
<style>
.hcav2vhso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.123 17.688c-6.547.283-19.688 12.624-22.42 19.36c0 0-6.223-2.88-10.645-4.334c-.016-3.251 1.41-4.786 1.41-4.786");
}

.i9243rqda {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.5 14.957l-14.696-4.004c-9.938.518-16.862 2.214-24.304 9.373l15.214 4.852C24 18.913 33.609 14.486 43.5 14.957");
}

.sa70z1ivg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 16.244c-10.472.283-18.558 7.662-23.362 14.868L7.185 26.355c.707-2.677 2.846-4.265 2.846-4.265");
}

.vd3fi28uo {
  cx: 22.87px;
  cy: 14.674px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.899px;
  ry: 1.413px;
}

</style>
