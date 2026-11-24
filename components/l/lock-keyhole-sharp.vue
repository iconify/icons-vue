<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnav8gbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-keyhole-sharp" /></template>
<style>
.xnav8gbon {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 9h16v12H4Zm7 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 1v2M8 9V7a4 4 0 1 1 8 0v2");
}

</style>
