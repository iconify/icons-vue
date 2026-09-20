<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ek7k-4b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:anchor-bold" /></template>
<style>
.ek7k-4b5s {
  fill: currentColor;
  d: path("M216 132a12 12 0 0 0-12 12c0 21.86-11.41 25.95-35.16 32.42c-9.12 2.49-19.61 5.36-28.84 10.69V132h28a12 12 0 0 0 0-24h-28V89.94a36 36 0 1 0-24 0V108H88a12 12 0 0 0 0 24h28v55.11c-9.23-5.33-19.72-8.2-28.84-10.69C63.41 170 52 165.86 52 144a12 12 0 0 0-24 0c0 41.17 30.54 49.5 52.84 55.58C104.59 206.05 116 210.14 116 232a12 12 0 0 0 24 0c0-21.86 11.41-25.95 35.16-32.42C197.46 193.5 228 185.17 228 144a12 12 0 0 0-12-12m-88-88a12 12 0 1 1-12 12a12 12 0 0 1 12-12");
}

</style>
