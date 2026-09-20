<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rxtauiqbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:caret-double-down-fill" /></template>
<style>
.rxtauiqbh {
  fill: currentColor;
  d: path("M215.39 132.94a8 8 0 0 1-1.73 8.72l-80 80a8 8 0 0 1-11.32 0l-80-80A8 8 0 0 1 48 128h60.69L42.34 61.66A8 8 0 0 1 48 48h160a8 8 0 0 1 5.66 13.66L147.31 128H208a8 8 0 0 1 7.39 4.94");
}

</style>
