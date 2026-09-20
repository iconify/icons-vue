<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lvc98vbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-line-up-right-bold" /></template>
<style>
.lvc98vbci {
  fill: currentColor;
  d: path("M228 216a12 12 0 0 1-12 12H40a12 12 0 0 1 0-24h176a12 12 0 0 1 12 12M80 180a12 12 0 0 0 8.49-3.51L180 85v67a12 12 0 0 0 24 0V56a12 12 0 0 0-12-12H96a12 12 0 0 0 0 24h67l-91.49 91.51A12 12 0 0 0 80 180");
}

</style>
