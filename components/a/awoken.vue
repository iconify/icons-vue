<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="yd1u9sbuw"/><ellipse class="hj09gibdk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:awoken" /></template>
<style>
.hj09gibdk {
  cx: 23.886px;
  cy: 23.751px;
  rx: 15.419px;
  ry: 15.47px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yd1u9sbuw {
  d: path("m5.69 34.435l36.62-.084L23.966 2.6z");
}

</style>
