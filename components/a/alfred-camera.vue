<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j82aexbnj"/><path class="uzjrpzr2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alfred-camera" /></template>
<style>
.j82aexbnj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.559 28.373V43.5l16.186-7.562Z");
}

.uzjrpzr2d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.745 35.938V20.302L24.019 4.5L8.255 20.302v15.633H23.56");
}

</style>
