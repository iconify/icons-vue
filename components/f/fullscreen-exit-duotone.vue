<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnpvo-xew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fullscreen-exit-duotone" /></template>
<style>
.tnpvo-xew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8h3a2 2 0 0 0 2-2V3m8 0v3a2 2 0 0 0 2 2h3m0 8h-3a2 2 0 0 0-2 2v3m-8 0v-3a2 2 0 0 0-2-2H3");
}

</style>
