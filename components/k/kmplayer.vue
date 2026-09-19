<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fdl-f1bvu"/><path class="s1sh7sbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kmplayer" /></template>
<style>
.fdl-f1bvu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 7.473v33.054l25.472-16.568z");
}

.s1sh7sbgk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.819 19.106L42.5 7.473v33.054L23.819 28.569");
}

</style>
