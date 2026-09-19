<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="exmpc3irr"/><path class="k-ox03dns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-globe-with-meridians" /></template>
<style>
.exmpc3irr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5v43c-6.573 0-11.902-9.626-11.902-21.5S17.427 2.5 24 2.5S35.902 12.126 35.902 24S30.573 45.5 24 45.5M45.5 24h-43m40.12-10.75H5.38m37.24 21.5H5.38");
}

.k-ox03dns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24c0 11.874 9.626 21.5 21.5 21.5S45.5 35.874 45.5 24S35.874 2.5 24 2.5S2.5 12.126 2.5 24");
}

</style>
