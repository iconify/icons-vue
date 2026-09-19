<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ykjq1zbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cookpad" /></template>
<style>
.ykjq1zbip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.022 25.77a7 7 0 0 0 1.728.23a7 7 0 1 0 0-14a7 7 0 0 0-5.541 2.75A7 7 0 0 0 23.25 8.5a7 7 0 0 0-6.555 4.594A7 7 0 0 0 5.25 18.5a7 7 0 0 0 6.225 6.945L9.662 39.5H32.25l2.168-16.805m-1.266 9.82H14.534");
}

</style>
