<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_i5qszfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-keyhole-sharp" /></template>
<style>
.x_i5qszfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 10h16v11H4Zm7 4a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 1v3m-3-8V6a3 3 0 0 1 6 0v4");
}

</style>
