<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="g-779hx0c"/><circle class="gkdfu0ngp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:go-and-big-c" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g-779hx0c {
  cx: 24px;
  cy: 24px;
  r: 14.333px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gkdfu0ngp {
  cx: 24px;
  cy: 24px;
  r: 7.167px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
