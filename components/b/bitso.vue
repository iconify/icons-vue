<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="js-4r5b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitso" /></template>
<style>
.js-4r5b2f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 16.084A7.895 7.895 0 0 1 31.916 24v16.693C38.198 37.682 42.5 31.4 42.5 24c0-10.24-8.26-18.5-18.5-18.5c-1.118 0-2.237.086-3.356.344v10.24zm0 15.832A7.895 7.895 0 0 1 16.084 24V5.5H5.5V24c0 10.24 8.26 18.5 18.5 18.5c1.118 0 2.237-.086 3.356-.344v-10.24z");
}

</style>
