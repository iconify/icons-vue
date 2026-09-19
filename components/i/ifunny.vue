<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="a_o4_673a"/><ellipse class="jxf98_oht"/><ellipse class="b6fjb4b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ifunny" /></template>
<style>
.a_o4_673a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38 26.87a14.24 14.24 0 0 1-27.89 0");
}

.b6fjb4b2p {
  cx: 30.61px;
  cy: 18.39px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.5px;
  ry: 4.22px;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jxf98_oht {
  cx: 17.2px;
  cy: 18.44px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.5px;
  ry: 4.22px;
}

</style>
