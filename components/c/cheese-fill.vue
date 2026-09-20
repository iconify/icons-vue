<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i32224d_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cheese-fill" /></template>
<style>
.i32224d_g {
  fill: currentColor;
  d: path("M184 32a7.8 7.8 0 0 0-2.3.34l-160 48A8 8 0 0 0 16 88v16a8 8 0 0 0 8 8h7.46c13.45 0 24.79 11 24.54 24.46A24 24 0 0 1 32 160h-8a8 8 0 0 0-8 8v24a8 8 0 0 0 8 8h200a16 16 0 0 0 16-16V88a56.06 56.06 0 0 0-56-56M80 184a32 32 0 0 1 64 0Zm88-48a32 32 0 0 1-31-40h62a32 32 0 0 1-31 40M78.51 80l106.61-32a40.06 40.06 0 0 1 38.07 32Z");
}

</style>
