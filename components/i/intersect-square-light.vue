<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="w_lj2b2pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:intersect-square-light" /></template>
<style>
.w_lj2b2pz {
  fill: currentColor;
  d: path("M216 90h-50V40a6 6 0 0 0-6-6H40a6 6 0 0 0-6 6v120a6 6 0 0 0 6 6h50v50a6 6 0 0 0 6 6h120a6 6 0 0 0 6-6V96a6 6 0 0 0-6-6M46 154V46h108v44H96a6 6 0 0 0-6 6v58Zm56-43.52L145.52 154H102Zm52 35L110.48 102H154ZM210 210H102v-44h58a6 6 0 0 0 6-6v-58h44Z");
}

</style>
