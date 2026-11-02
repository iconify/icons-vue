<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z81phrbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-charging-fill" /></template>
<style>
.z81phrbao {
  fill: currentColor;
  d: path("M5 6h11a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3m6.414 5l.293-.293a.999.999 0 1 0-1.414-1.414l-2 2A1 1 0 0 0 9 13h.586l-.293.293a.999.999 0 1 0 1.414 1.414l2-2A1 1 0 0 0 12 11ZM22 10v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

</style>
