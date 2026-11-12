<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scvqi5bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ethernet-fill-round" /></template>
<style>
.scvqi5bul {
  fill: currentColor;
  d: path("M19 18h-1v2a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-2H5a3 3 0 0 1-3-3V8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v7a3 3 0 0 1-3 3M7 8a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Zm4 0a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Zm4 3V8a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0m4-3a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Z");
}

</style>
