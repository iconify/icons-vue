<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owfc3oblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-search-fill-round" /></template>
<style>
.owfc3oblc {
  fill: currentColor;
  d: path("M18 11a7 7 0 0 0-5.612-6.861A7 7 0 0 0 4.55 8.276a6.99 6.99 0 0 0 1.5 7.674A6.97 6.97 0 0 0 11 18a1 1 0 0 1 0 2A9 9 0 0 1 6.028 3.498a9 9 0 0 1 8.476-.79A8.99 8.99 0 0 1 20 11a1 1 0 0 1-2 0m-6-4v3h2a1 1 0 0 1 0 2h-3a1 1 0 0 1-1-1V7a1 1 0 0 1 2 0m9.321 12.907l1.386 1.386a.999.999 0 1 1-1.414 1.414l-1.386-1.386a3.83 3.83 0 1 1 1.414-1.414m-1.626-1.218a1.83 1.83 0 1 0-3.39-1.376a1.83 1.83 0 0 0 3.39 1.376");
}

</style>
