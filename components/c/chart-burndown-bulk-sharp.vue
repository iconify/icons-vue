<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dhpxnuokf"/><path class="bmmvoibrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-burndown-bulk-sharp" /></template>
<style>
.bmmvoibrk {
  d: path("M11 6c.351 0 .677.184.857.486L14.566 11H17c.379 0 .725.214.894.553l4 8a1 1 0 1 1-1.788.894L16.382 13H14a1 1 0 0 1-.857-.486L10.434 8H7a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.dhpxnuokf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 19h17a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0Z");
}

</style>
