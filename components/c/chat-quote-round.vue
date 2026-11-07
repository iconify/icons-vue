<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_1m3obiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-quote-round" /></template>
<style>
.q_1m3obiw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17H9c-1.28 0-2.36.36-3 1l-1 1c-.738.738-2-.524-2-2V7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4zM8 8h2v2l-2 2m6-4h2v2l-2 2");
}

</style>
