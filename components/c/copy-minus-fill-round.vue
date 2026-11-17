<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0oi47bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-minus-fill-round" /></template>
<style>
.w0oi47bcq {
  fill: currentColor;
  d: path("M11 2h6a5 5 0 0 1 5 5v6a5 5 0 0 1-5 5h-6a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5M4 9v8a3 3 0 0 0 3 3h8a1 1 0 0 1 0 2H7a5 5 0 0 1-5-5V9a1 1 0 0 1 2 0m7 0a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2Z");
}

</style>
