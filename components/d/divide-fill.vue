<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ghj7wnhff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:divide-fill" /></template>
<style>
.ghj7wnhff {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m-80 32a16 16 0 1 1-16 16a16 16 0 0 1 16-16m0 128a16 16 0 1 1 16-16a16 16 0 0 1-16 16m56-56H72a8 8 0 0 1 0-16h112a8 8 0 0 1 0 16");
}

</style>
