<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m5_91ce9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:delta-force-alt" /></template>
<style>
.m5_91ce9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.979L5.5 40.02h37L27.983 14.878l-8.07 13.983h3.676l-2.723 4.717l6.988-5.732h-3.677l2.839-4.918l7.063 12.23H13.921L24 17.703z");
}

</style>
