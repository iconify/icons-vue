<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btcmmqbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-geothermal-fill" /></template>
<style>
.btcmmqbvh {
  fill: currentColor;
  d: path("M15.333 16H13v2h5a1 1 0 0 1 1 1v2a1 1 0 0 1-2 0v-1h-2v1a1 1 0 0 1-2 0v-1h-2v1a1 1 0 0 1-2 0v-1H7v1a1 1 0 0 1-2 0v-2a1 1 0 0 1 1-1h5v-2H8.667a3 3 0 0 1-3-3V8.574a3 3 0 0 1 1.024-2.258L10.024 3.4a3 3 0 0 1 3.952 0l3.333 2.916a3 3 0 0 1 1.024 2.258V13a3 3 0 0 1-3 3");
}

</style>
