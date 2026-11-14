<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ooj7w_bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ai-chat-archive" /></template>
<style>
.ooj7w_bpd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3H17a2.5 2.5 0 0 1 2.5 2.5v5A2.5 2.5 0 0 1 17 13h-6.5l-4 3.5V13h-1A2.5 2.5 0 0 1 3 10.5v-5A2.5 2.5 0 0 1 5.5 3ZM15 16h6.5v2.25H15Zm.75 2.25v2.25a1 1 0 0 0 1 1h3a1 1 0 0 0 1-1v-2.25");
}

</style>
