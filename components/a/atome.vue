<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vx3z690tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:atome" /></template>
<style>
.vx3z690tn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 39.639L24 8.361m5.928 10.022L24 8.361m18.5 31.278l-7.276-12.301m-22.449.001A15.56 15.56 0 0 0 24 32.103c6.318 0 11.76-3.756 14.213-9.156");
}

</style>
