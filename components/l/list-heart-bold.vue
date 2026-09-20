<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pggv_j13l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:list-heart-bold" /></template>
<style>
.pggv_j13l {
  fill: currentColor;
  d: path("M124 192a12 12 0 0 1-12 12H40a12 12 0 0 1 0-24h72a12 12 0 0 1 12 12M40 76h176a12 12 0 0 0 0-24H40a12 12 0 0 0 0 24m0 64h56a12 12 0 0 0 0-24H40a12 12 0 0 0 0 24m212 4c0 17-9.53 33.56-28.32 49.22a151.5 151.5 0 0 1-26.31 17.51a12 12 0 0 1-10.74 0a151.5 151.5 0 0 1-26.31-17.51C141.53 177.56 132 161 132 144a36 36 0 0 1 60-26.81A36 36 0 0 1 252 144m-24 0a12 12 0 0 0-24 0a12 12 0 0 1-24 0a12 12 0 0 0-24 0c0 17.23 22.85 34.43 36 42.29c13.14-7.85 36-25.06 36-42.29");
}

</style>
