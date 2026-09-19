<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lx8wpeb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:activearmor" /></template>
<style>
.lx8wpeb_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.032 39.307c-14.097 3.434-27.257-5.922-27.51-21.317m17.01-15.008c10.904 10.457 9.656 27.171-3.896 35.296M3.27 29.618C7.565 15.696 22.419 9.203 35.768 16.96M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
