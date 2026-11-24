<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y36oh4ecc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-edit-corner-fill-round" /></template>
<style>
.y36oh4ecc {
  fill: currentColor;
  d: path("M21.901 8H2.099A5.01 5.01 0 0 1 7 4h10a5.01 5.01 0 0 1 4.901 4M10 10v9a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5v-5Zm2 11v-3c0-.265.105-.52.293-.707l5-5a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-5 5A1 1 0 0 1 16 22h-3a1 1 0 0 1-1-1");
}

</style>
