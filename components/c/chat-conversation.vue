<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n06oxibod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-conversation" /></template>
<style>
.n06oxibod {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 10V5a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H8c-.64 0-1.36.36-2 1l-2 2c-.369.369-1-.262-1-1zm16-1a2 2 0 0 1 2 2v8c0 .738-.631 1.369-1 1l-2-2c-.64-.64-1.36-1-2-1H9");
}

</style>
