<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="oqorqniqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:align-center-vertical-simple-fill" /></template>
<style>
.oqorqniqm {
  fill: currentColor;
  d: path("M216 128a8 8 0 0 1-8 8h-32v72a16 16 0 0 1-16 16H96a16 16 0 0 1-16-16v-72H48a8 8 0 0 1 0-16h32V48a16 16 0 0 1 16-16h64a16 16 0 0 1 16 16v72h32a8 8 0 0 1 8 8");
}

</style>
