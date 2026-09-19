<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="kgkmrccgd"/><path class="ci4j2zbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ion-launcher-alt-1" /></template>
<style>
.ci4j2zbwf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.91 19.595L24 8.5l19.09 11.095");
}

.kgkmrccgd {
  cx: 24px;
  cy: 27.753px;
  r: 11.747px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
