<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgaf5pphe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:data-packet-fill" /></template>
<style>
.dgaf5pphe {
  fill: currentColor;
  d: path("M22 8H8V7a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3ZM5 7a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm17 3v7a3 3 0 0 1-3 3h-8a3 3 0 0 1-3-3v-7ZM5 11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm9 2a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Zm4 3v-3a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0M5 15a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
