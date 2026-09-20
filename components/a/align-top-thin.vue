<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kp-byubmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:align-top-thin" /></template>
<style>
.kp-byubmp {
  fill: currentColor;
  d: path("M220 40a4 4 0 0 1-4 4H40a4 4 0 0 1 0-8h176a4 4 0 0 1 4 4m-16 40v96a12 12 0 0 1-12 12h-40a12 12 0 0 1-12-12V80a12 12 0 0 1 12-12h40a12 12 0 0 1 12 12m-8 0a4 4 0 0 0-4-4h-40a4 4 0 0 0-4 4v96a4 4 0 0 0 4 4h40a4 4 0 0 0 4-4Zm-80 0v136a12 12 0 0 1-12 12H64a12 12 0 0 1-12-12V80a12 12 0 0 1 12-12h40a12 12 0 0 1 12 12m-8 0a4 4 0 0 0-4-4H64a4 4 0 0 0-4 4v136a4 4 0 0 0 4 4h40a4 4 0 0 0 4-4Z");
}

</style>
