<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="zi9-fjbut"/><path class="ulq81kxvv"/><path class="zug1jpb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:idos" /></template>
<style>
.ulq81kxvv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.658 7.088v23.775l1.304 1.267l18.145.004l1.303-1.286V7.088l-1.303-1.416l-2.294-.005V4.5H10.318v1.167H7.962z");
}

.zi9-fjbut {
  cx: 38.304px;
  cy: 21.081px;
  r: 3.038px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zug1jpb-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.23 11.303v9.885h15.747v-9.885zM9.065 25.2H14.2v3.076H9.065zm10.804 0h5.135v3.076h-5.135zM11.744 7.075h10.72v1.729h-10.72zm-2.009 32.03l1.665-5.487h3.076l-1.664 5.487zm14.599 0l-1.664-5.487h-3.077l1.665 5.487zM31.28 43.5h4.77l3.879-17.62h-8.044l-.866 3.934h3.274z");
}

</style>
