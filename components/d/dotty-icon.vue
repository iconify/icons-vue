<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="aq513obhb"/><path class="ckg44tbvp"/><rect class="tcnmssbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dotty-icon" /></template>
<style>
.aq513obhb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.45 29.002v3.446A2.55 2.55 0 0 1 26.898 35a2.54 2.54 0 0 1-1.805-.748");
}

.ckg44tbvp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.45 24.79v4.212a2.552 2.552 0 1 1-5.105 0v-4.211m-4.302-.001v8.741A1.47 1.47 0 0 0 21.512 35h.44m-3.451-7.785h3.084M32.132 12v8.74c0 .812.658 1.47 1.469 1.47h.44m-3.451-7.786h3.084M19.24 17.998a2.552 2.552 0 1 0-5.105 0v1.659a2.552 2.552 0 1 0 5.105 0m.001 2.552V12");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.tcnmssbod {
  width: 6.764px;
  height: 10.209px;
  x: 21.717px;
  y: 12px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.382px;
  ry: 3.382px;
}

</style>
