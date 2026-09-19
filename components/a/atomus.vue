<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="gznplfboo"/><ellipse transform="rotate(-30 24 24)" class="t0wbdbc0x"/><ellipse transform="rotate(-60 24 24)" class="gznplfboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:atomus" /></template>
<style>
.gznplfboo {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.024px;
  ry: 21.5px;
}

.t0wbdbc0x {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 21.5px;
  ry: 7.024px;
}

</style>
