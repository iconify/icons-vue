<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kodf7cbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-curve-sharp" /></template>
<style>
.kodf7cbhp {
  fill: currentColor;
  d: path("M18 20q0-2.9-1.1-5.45t-3-4.45t-4.45-3T4 6V4q3.3 0 6.213 1.263T15.3 8.7t3.438 5.088T20 20z");
}

</style>
