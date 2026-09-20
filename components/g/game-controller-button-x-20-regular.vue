<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d8x55ss1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:game-controller-button-x-20-regular" /></template>
<style>
.d8x55ss1q {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16m0 1a7 7 0 1 0 0 14a7 7 0 0 0 0-14m2.646 3.646a.5.5 0 1 1 .707.708L10.708 10l2.646 2.646a.5.5 0 1 1-.707.707L10 10.708l-2.646 2.646a.5.5 0 1 1-.708-.707L9.293 10L6.646 7.354a.5.5 0 1 1 .708-.708L10 9.293z");
}

</style>
