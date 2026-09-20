<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhvbb4bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-alt-outline-sharp" /></template>
<style>
.mhvbb4bsi {
  fill: currentColor;
  d: path("M10 20v-7L2.95 4h18.1L14 13v7zm2-7.7L16.95 6h-9.9zm0 0");
}

</style>
