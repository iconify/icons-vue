<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vp2qaublw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:infinity-light" /></template>
<style>
.vp2qaublw {
  fill: currentColor;
  d: path("M246 128a54 54 0 0 1-92.18 38.18a3 3 0 0 1-.25-.26l-60-67.74a42 42 0 1 0 0 59.64l8.57-9.67a6 6 0 1 1 9 8l-8.69 9.81a3 3 0 0 1-.25.26a54 54 0 1 1 0-76.36a3 3 0 0 1 .25.26l60 67.74a42 42 0 1 0 0-59.64l-8.57 9.67a6 6 0 1 1-9-8l8.69-9.81a3 3 0 0 1 .25-.26A54 54 0 0 1 246 128");
}

</style>
