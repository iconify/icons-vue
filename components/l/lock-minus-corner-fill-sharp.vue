<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exlj4h52t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-minus-corner-fill-sharp" /></template>
<style>
.exlj4h52t {
  fill: currentColor;
  d: path("M4 8h3V7a5 5 0 0 1 10 0v1h3a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-8v9a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1m11 0V7a3 3 0 1 0-6 0v1Zm0 8h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

</style>
