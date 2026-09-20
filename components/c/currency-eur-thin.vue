<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="iyq2ztf2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:currency-eur-thin" /></template>
<style>
.iyq2ztf2k {
  fill: currentColor;
  d: path("M187 195a4 4 0 0 1-.31 5.65A76 76 0 0 1 60.11 148H40a4 4 0 0 1 0-8h20v-24H40a4 4 0 0 1 0-8h20.11a76 76 0 0 1 126.56-52.65a4 4 0 1 1-5.34 6A68 68 0 0 0 68.13 108H136a4 4 0 0 1 0 8H68v24h52a4 4 0 0 1 0 8H68.13a68 68 0 0 0 113.2 46.69a4 4 0 0 1 5.67.31");
}

</style>
