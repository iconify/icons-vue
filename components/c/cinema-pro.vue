<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ewtjcgbht"/><circle class="i7z762-kp"/><path class="l-49l_obv"/><circle class="dtouqvbrb"/><path class="l3k3q6b9e"/><circle class="skyz4fflw"/><path class="f5oza1m5z"/><path class="tzo0dpkil"/><path class="v8ouz-b0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cinema-pro" /></template>
<style>
.dtouqvbrb {
  cx: 34.972px;
  cy: 30.758px;
  r: 4.386px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ewtjcgbht {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.004 31.569H4.5V18.828h21.277v13.994h-5.514l-1.755-3.04H8.972zm15.773-11.345h3.28l1.849-3.203m.64-4.315l-.666-.666h-4.992m-4.528 1.639v1.682h-5.536v3.467");
}

.f5oza1m5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.472 20.97v15.358");
}

.i7z762-kp {
  cx: 32.238px;
  cy: 15.014px;
  r: 2.409px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l-49l_obv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.004 31.569l1.417 2.454h6.051l1.469 2.543h10.518v-3.744h-3.682v-1.253");
}

.l3k3q6b9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.777 22.455h4.357l.997-.997h3.698v-.488h8.63v10.77h-4.212m-8.653-1.253h-4.817M43.5 33.321V19.398m-17.612-7.964H10.103v3.051h2.06l.466-.806h13.259Z");
}

.skyz4fflw {
  cx: 34.972px;
  cy: 30.758px;
  r: 2.326px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tzo0dpkil {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("m29.459 34.694l3.583.003m3.847.006l5.603-.01");
}

.v8ouz-b0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.112 22.496h7.333v4.532h-7.333z");
}

</style>
