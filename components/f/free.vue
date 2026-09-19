<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="plgagap5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:free" /></template>
<style>
.plgagap5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.6 42.5l13.947-27.972c2.47-4.955 9.052-11.01 16.852-8.4M11.587 18.119h20.194");
}

</style>
