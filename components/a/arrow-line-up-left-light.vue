<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mffce2b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-line-up-left-light" /></template>
<style>
.mffce2b2t {
  fill: currentColor;
  d: path("M230 208a6 6 0 0 1-6 6H48a6 6 0 0 1 0-12h176a6 6 0 0 1 6 6M72 150a6 6 0 0 0 6-6V62.49l101.76 101.75a6 6 0 0 0 8.48-8.48L86.49 54H168a6 6 0 0 0 0-12H72a6 6 0 0 0-6 6v96a6 6 0 0 0 6 6");
}

</style>
