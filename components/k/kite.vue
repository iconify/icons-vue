<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phwh7-v0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kite" /></template>
<style>
.phwh7-v0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 13l-4 4a1.414 1.414 0 0 1-2 0L3 9l9-6l9 6zm-5-9v13M4 9h16m-8 9c0 3 5 3 7 3");
}

</style>
