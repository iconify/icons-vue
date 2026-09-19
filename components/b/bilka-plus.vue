<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="n76bxqtui"/><circle class="lacl3kq-i"/><path class="hjj3dkehd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bilka-plus" /></template>
<style>
.hjj3dkehd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.265 21.428v6.679m2.106-9.983v10.081m2.108-10.081v10.081m0-2.142l4.571-4.537m-3.174 3.151l3.682 3.528m6.272-2.412c0 1.386-1.143 2.52-2.54 2.52s-2.54-1.134-2.54-2.52v-1.64c0-1.386 1.144-2.52 2.54-2.52s2.54 1.134 2.54 2.52m0 4.16v-6.68m1.845 3.34H39.5m-2.412-2.412v4.824");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.lacl3kq-i {
  cx: 17.265px;
  cy: 18.404px;
  r: 0.75px;
  fill: currentColor;
}

.n76bxqtui {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.69 23.283c1.397 0 2.54 1.135 2.54 2.52s-1.143 2.522-2.54 2.522H8.5V18.243h4.19c1.397 0 2.54 1.134 2.54 2.52s-1.143 2.52-2.54 2.52m0 0H8.5");
}

</style>
