<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hpqdm4b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:data-monitor" /></template>
<style>
.hpqdm4b7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.93 13.834V31.02M13.12 16.337v17.83M4.5 24.93l8.62 9.236l8.62-9.236m4.62-2.503l8.57-8.593l8.57 8.593");
}

</style>
