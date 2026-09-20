<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="e_38stboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:beer-stein-bold" /></template>
<style>
.e_38stboi {
  fill: currentColor;
  d: path("M216 84h-12V72a44.05 44.05 0 0 0-44-44h-9.73c-12.5-10.22-29.09-16-46.27-16c-37.5 0-68 26.92-68 60v136a20 20 0 0 0 20 20h128a20 20 0 0 0 20-20v-4h12a28 28 0 0 0 28-28v-64a28 28 0 0 0-28-28M104 36c12.85 0 25 4.62 33.44 12.67a12 12 0 0 0 8.3 3.33H160a20 20 0 0 1 19.6 16H60.28C62.72 50 81.39 36 104 36m76 168H60V92h120Zm40-28a4 4 0 0 1-4 4h-12v-72h12a4 4 0 0 1 4 4Zm-112-56v56a12 12 0 0 1-24 0v-56a12 12 0 0 1 24 0m48 0v56a12 12 0 0 1-24 0v-56a12 12 0 0 1 24 0");
}

</style>
