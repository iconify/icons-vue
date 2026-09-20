<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="aihmlfbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:check-square-offset-fill" /></template>
<style>
.aihmlfbaz {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16M80 200a8 8 0 0 1-5.66-2.34l-16-16a8 8 0 0 1 11.32-11.32L80 180.69l34.34-34.35a8 8 0 0 1 11.32 11.32l-40 40A8 8 0 0 1 80 200m120-8a8 8 0 0 1-8 8h-56a8 8 0 0 1 0-16h48V72H72v64a8 8 0 0 1-16 0V64a8 8 0 0 1 8-8h128a8 8 0 0 1 8 8Z");
}

</style>
