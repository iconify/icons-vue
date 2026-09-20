<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nqko3nb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:identification-card-bold" /></template>
<style>
.nqko3nb7p {
  fill: currentColor;
  d: path("M148 108a12 12 0 0 1 12-12h28a12 12 0 0 1 0 24h-28a12 12 0 0 1-12-12m40 28h-20a12 12 0 0 0 0 24h20a12 12 0 0 0 0-24m48-80v144a20 20 0 0 1-20 20H40a20 20 0 0 1-20-20V56a20 20 0 0 1 20-20h176a20 20 0 0 1 20 20m-24 4H44v136h168ZM58.28 159.37A43.8 43.8 0 0 1 71.53 142a36 36 0 1 1 56.94 0a43.84 43.84 0 0 1 13.26 17.37a12 12 0 0 1-22.15 9.26C116.48 161.19 108.42 156 100 156s-16.47 5.2-19.59 12.63a12 12 0 1 1-22.13-9.26M88 120a12 12 0 1 0 12-12a12 12 0 0 0-12 12");
}

</style>
