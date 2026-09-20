<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pne6nqbww"/><rect class="uhx3m_1tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flatastic" /></template>
<style>
.pne6nqbww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.7 13.3v21.6c0 2 1.6 3.6 3.6 3.6h1.1m-16.6 0V14.6c0-2.8 2.3-5.1 5.1-5.1c.5 0 1.1 0 1.6.1m-10.9 9.7h19.9");
}

.uhx3m_1tm {
  width: 31px;
  height: 39px;
  x: 8.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
