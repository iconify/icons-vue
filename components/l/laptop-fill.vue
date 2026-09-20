<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bgco4nbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:laptop-fill" /></template>
<style>
.bgco4nbez {
  fill: currentColor;
  d: path("M232 168h-8V72a24 24 0 0 0-24-24H56a24 24 0 0 0-24 24v96h-8a8 8 0 0 0-8 8v16a24 24 0 0 0 24 24h176a24 24 0 0 0 24-24v-16a8 8 0 0 0-8-8M112 72h32a8 8 0 0 1 0 16h-32a8 8 0 0 1 0-16m112 120a8 8 0 0 1-8 8H40a8 8 0 0 1-8-8v-8h192Z");
}

</style>
