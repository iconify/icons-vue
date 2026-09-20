<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mij7hwcae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chart-line-down-thin" /></template>
<style>
.mij7hwcae {
  fill: currentColor;
  d: path("M228 208a4 4 0 0 1-4 4H32a4 4 0 0 1-4-4V48a4 4 0 0 1 8 0v14.34l60 60l29.17-29.17a4 4 0 0 1 5.66 0L196 158.34V128a4 4 0 0 1 8 0v40a4 4 0 0 1-.08.78a3 3 0 0 1-.1.34a3 3 0 0 1-.13.41a3 3 0 0 1-.2.39c-.05.1-.1.2-.16.3a4.2 4.2 0 0 1-1.11 1.11l-.31.16a4 4 0 0 1-.38.2a3 3 0 0 1-.41.13a3 3 0 0 1-.34.1a4 4 0 0 1-.78.08h-40a4 4 0 0 1 0-8h30.34L128 101.66l-29.17 29.17a4 4 0 0 1-5.66 0L36 73.66V204h188a4 4 0 0 1 4 4");
}

</style>
