<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ust3-pbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-thermometer-corner-fill" /></template>
<style>
.ust3-pbho {
  fill: currentColor;
  d: path("M17.714 9H10a.997.997 0 0 0-1 1v11a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l4.397 3.847A1.001 1.001 0 0 1 17.714 9M14.5 16.472V13.5a2.5 2.5 0 1 1 5 0v2.972a3.25 3.25 0 1 1-5 0m2-2.972v3.373a1 1 0 0 1-.333.745a1.25 1.25 0 1 0 1.666 0a1 1 0 0 1-.333-.745V13.5a.5.5 0 0 0-1 0");
}

</style>
