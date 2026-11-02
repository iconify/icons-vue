<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etl9vx6sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bus-sharp" /></template>
<style>
.etl9vx6sf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 3h14v16H5zm2 16h2v2H7Zm8 0h2v2h-2ZM5 13h14M9 6h6M8 16h.01M16 16h.01");
}

</style>
