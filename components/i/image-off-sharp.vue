<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9pugkbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-off-sharp" /></template>
<style>
.y9pugkbgx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3h12v12m0 6H3V3m0 14l7-7m6-3a1 1 0 1 0 2 0a1 1 0 0 0-2 0M2 2l20 20");
}

</style>
