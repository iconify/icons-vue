<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1nxi0v9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gift-sharp" /></template>
<style>
.z1nxi0v9f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7h18v4H3Zm2 4v10h14V11m-7-4H9C7 7 6 6 6 5c0-2 2-2 3-1zm0 0h3c2 0 3-1 3-2c0-2-2-2-3-1zm0 0v14");
}

</style>
