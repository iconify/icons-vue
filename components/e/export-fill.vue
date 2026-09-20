<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ghnd9lb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:export-fill" /></template>
<style>
.ghnd9lb4u {
  fill: currentColor;
  d: path("M216 112v96a16 16 0 0 1-16 16H56a16 16 0 0 1-16-16v-96a16 16 0 0 1 16-16h64v48a8 8 0 0 0 16 0V96h64a16 16 0 0 1 16 16m-80-68.69l26.34 26.35a8 8 0 0 0 11.32-11.32l-40-40a8 8 0 0 0-11.32 0l-40 40a8 8 0 0 0 11.32 11.32L120 43.31V96h16Z");
}

</style>
