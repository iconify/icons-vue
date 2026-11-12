<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eofa2-c6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:data-packet-fill-round" /></template>
<style>
.eofa2-c6z {
  fill: currentColor;
  d: path("M21.901 8H8.099A5.01 5.01 0 0 1 13 4h4a5.01 5.01 0 0 1 4.901 4M5 7a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm17 3v5a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20h-4a5 5 0 0 1-5-5v-5ZM5 11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm9 2a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Zm4 3v-3a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0M5 15a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
