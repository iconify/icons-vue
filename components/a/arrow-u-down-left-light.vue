<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pq_3grr4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-u-down-left-light" /></template>
<style>
.pq_3grr4m {
  fill: currentColor;
  d: path("M230 112a62.07 62.07 0 0 1-62 62H46.49l37.75 37.76a6 6 0 1 1-8.48 8.48l-48-48a6 6 0 0 1 0-8.48l48-48a6 6 0 0 1 8.48 8.48L46.49 162H168a50 50 0 0 0 0-100H80a6 6 0 0 1 0-12h88a62.07 62.07 0 0 1 62 62");
}

</style>
