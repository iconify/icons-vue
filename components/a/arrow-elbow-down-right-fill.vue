<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kgdxpyb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-elbow-down-right-fill" /></template>
<style>
.kgdxpyb7m {
  fill: currentColor;
  d: path("m221.66 181.66l-48 48A8 8 0 0 1 160 224v-40H72a8 8 0 0 1-8-8V32a8 8 0 0 1 16 0v136h80v-40a8 8 0 0 1 13.66-5.66l48 48a8 8 0 0 1 0 11.32");
}

</style>
