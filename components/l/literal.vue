<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s8j4oxb-s"/><path class="zh-_tqb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:literal" /></template>
<style>
.s8j4oxb-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.205 13.205l7.717 7.717M13.205 42.5L5.5 34.795V5.5h29.295v29.295H20.922V20.923h6.167m.001 6.167l7.705 7.705");
}

.zh-_tqb7l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.923 27.09h6.166V13.204H13.205V42.5H42.5V13.205L34.795 5.5");
}

</style>
