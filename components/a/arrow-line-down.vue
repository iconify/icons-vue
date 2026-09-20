<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fc5euxugb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-line-down" /></template>
<style>
.fc5euxugb {
  fill: currentColor;
  d: path("M50.34 117.66a8 8 0 0 1 11.32-11.32L120 164.69V32a8 8 0 0 1 16 0v132.69l58.34-58.35a8 8 0 0 1 11.32 11.32l-72 72a8 8 0 0 1-11.32 0ZM216 208H40a8 8 0 0 0 0 16h176a8 8 0 0 0 0-16");
}

</style>
