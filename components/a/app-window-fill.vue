<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nd7ejmbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:app-window-fill" /></template>
<style>
.nd7ejmbfp {
  fill: currentColor;
  d: path("M216 40H40a16 16 0 0 0-16 16v144a16 16 0 0 0 16 16h176a16 16 0 0 0 16-16V56a16 16 0 0 0-16-16M68 96a12 12 0 1 1 12-12a12 12 0 0 1-12 12m40 0a12 12 0 1 1 12-12a12 12 0 0 1-12 12");
}

</style>
