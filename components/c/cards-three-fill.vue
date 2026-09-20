<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="l-fbkcc_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cards-three-fill" /></template>
<style>
.l-fbkcc_j {
  fill: currentColor;
  d: path("M224 104v96a16 16 0 0 1-16 16H48a16 16 0 0 1-16-16v-96a16 16 0 0 1 16-16h160a16 16 0 0 1 16 16M56 72h144a8 8 0 0 0 0-16H56a8 8 0 0 0 0 16m16-32h112a8 8 0 0 0 0-16H72a8 8 0 0 0 0 16");
}

</style>
