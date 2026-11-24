<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yce347bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-search-corner-fill-sharp" /></template>
<style>
.yce347bfx {
  fill: currentColor;
  d: path("M22 5v3H2V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1M2 10h8v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm17.321 7.907l2.386 2.386a.999.999 0 1 1-1.414 1.414l-2.386-2.386a3.83 3.83 0 1 1 1.414-1.414m-2.028-.614a1.829 1.829 0 1 0-2.587-2.586a1.829 1.829 0 0 0 2.587 2.586");
}

</style>
