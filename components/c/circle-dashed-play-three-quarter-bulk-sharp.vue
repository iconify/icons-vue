<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dl-9g0b0v"/><path class="x-4ip0bbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-play-three-quarter-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dl-9g0b0v {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 8a1 1 0 0 1 1.555-.832l6 4a1 1 0 0 1 0 1.664l-6 4A1 1 0 0 1 9 16Z");
}

.x-4ip0bbk {
  d: path("M4 11.94A7.997 7.997 0 0 0 11.998 20H12a8.001 8.001 0 0 0 5.657-13.657a7.99 7.99 0 0 0-6.908-2.244a1 1 0 0 1-.313-1.976a10 10 0 0 1 11.542 9.215a10 10 0 0 1-8.656 10.576A10.004 10.004 0 0 1 2.123 10.436a1 1 0 0 1 1.976.313A8 8 0 0 0 4 11.94m3.616-7.645v.001a1 1 0 0 1-.318 1.232a8 8 0 0 0-1.77 1.77A1 1 0 0 1 3.91 6.122A10 10 0 0 1 6.122 3.91a1 1 0 0 1 1.494.385M9 8a1 1 0 0 1 1.555-.832l6 4a1 1 0 0 1 0 1.664l-6 4A1 1 0 0 1 9 16Zm2 6.131L14.197 12L11 9.869Z");
}

</style>
