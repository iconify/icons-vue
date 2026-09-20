<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gx0bp1agn"/><path class="xf2rhbixa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dmm" /></template>
<style>
.gx0bp1agn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.366 5.5h16.768c10.21 0 18.5 8.29 18.5 18.5s-8.29 18.5-18.5 18.5H6.366z");
}

.xf2rhbixa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.748 24l-13.496-7.793v15.586z");
}

</style>
