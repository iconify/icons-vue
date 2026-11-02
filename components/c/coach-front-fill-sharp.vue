<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s27mvqqww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coach-front-fill-sharp" /></template>
<style>
.s27mvqqww {
  fill: currentColor;
  d: path("M3 18V7a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v11a1 1 0 0 1-1 1h-1v1a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1H9v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1H4a1 1 0 0 1-1-1M16 4H8a3 3 0 0 0-3 3v4h14V7a3 3 0 0 0-3-3M8.01 14H8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m8 0H16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
