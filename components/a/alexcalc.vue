<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="owxxebcrj"/><circle class="cgg-n7e9y"/><path class="u99zgq3sp"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alexcalc" /></template>
<style>
.cgg-n7e9y {
  cx: 28.401px;
  cy: 10.871px;
  r: 0.75px;
  fill: currentColor;
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.owxxebcrj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.4 14.456v10.303c0 1.897-1.522 3.434-3.401 3.434c-.94 0-1.79-.384-2.406-1.006");
}

.u99zgq3sp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.529 35.171A5.366 5.366 0 0 1 9.5 32.513v-3.488a5.366 5.366 0 1 1 10.732 0v1.744H9.5m29-9.296a3.19 3.19 0 1 1-6.378 0v-7.585a3.19 3.19 0 1 1 6.378 0zm-6.378-3.793H38.5");
}

</style>
