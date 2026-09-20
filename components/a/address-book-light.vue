<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="j4w2owbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:address-book-light" /></template>
<style>
.j4w2owbvg {
  fill: currentColor;
  d: path("M159.11 142.13a38 38 0 1 0-46.22 0A65.75 65.75 0 0 0 83.2 164.4a6 6 0 0 0 9.6 7.2a54 54 0 0 1 86.4 0a6 6 0 0 0 9.6-7.2a65.75 65.75 0 0 0-29.69-22.27M110 112a26 26 0 1 1 26 26a26 26 0 0 1-26-26m98-86H64a14 14 0 0 0-14 14v26H32a6 6 0 0 0 0 12h18v44H32a6 6 0 0 0 0 12h18v44H32a6 6 0 0 0 0 12h18v26a14 14 0 0 0 14 14h144a14 14 0 0 0 14-14V40a14 14 0 0 0-14-14m2 190a2 2 0 0 1-2 2H64a2 2 0 0 1-2-2V40a2 2 0 0 1 2-2h144a2 2 0 0 1 2 2Z");
}

</style>
