<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xnpcxgbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-fat-lines-right-light" /></template>
<style>
.xnpcxgbpy {
  fill: currentColor;
  d: path("m236.24 123.76l-96-96A6 6 0 0 0 130 32v42h-26a6 6 0 0 0-6 6v96a6 6 0 0 0 6 6h26v42a6 6 0 0 0 10.24 4.24l96-96a6 6 0 0 0 0-8.48M142 209.51V176a6 6 0 0 0-6-6h-26V86h26a6 6 0 0 0 6-6V46.49L223.51 128ZM46 80v96a6 6 0 0 1-12 0V80a6 6 0 0 1 12 0m32 0v96a6 6 0 0 1-12 0V80a6 6 0 0 1 12 0");
}

</style>
