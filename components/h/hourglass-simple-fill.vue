<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rr2cdsbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:hourglass-simple-fill" /></template>
<style>
.rr2cdsbce {
  fill: currentColor;
  d: path("M211.31 196.69A16 16 0 0 1 200 224H56a16 16 0 0 1-11.32-27.31a2 2 0 0 0 .13-.13L116.43 128L44.82 59.44a2 2 0 0 0-.13-.13A16 16 0 0 1 56 32h144a16 16 0 0 1 11.32 27.31a2 2 0 0 0-.13.13L139.57 128l71.61 68.56a2 2 0 0 0 .13.13");
}

</style>
