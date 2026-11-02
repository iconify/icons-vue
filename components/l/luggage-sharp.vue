<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp7rijbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:luggage-sharp" /></template>
<style>
.sp7rijbjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19H5V7h14v12h-2m-6 0h2m-6 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0m6 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0M9 7V3h6v4");
}

</style>
