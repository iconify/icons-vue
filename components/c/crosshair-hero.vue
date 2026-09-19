<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l-2djqbrb"/><circle class="jnytizb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:crosshair-hero" /></template>
<style>
.jnytizb3q {
  cx: 24.124px;
  cy: 24.179px;
  r: 1.651px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l-2djqbrb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.72 8.94l-6.715 12.83L43.5 28.323m-39-8.453l12.688 6.47l-6.853 12.72");
}

</style>
