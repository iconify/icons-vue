<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-27dc7pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-garage-open-round" /></template>
<style>
.q-27dc7pe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13h2a2 2 0 0 1 2 2v4a2 2 0 1 0 4 0v-7.185a4 4 0 0 0-1.366-3.01l-4-3.5a4 4 0 0 0-5.268 0l-4 3.5A4 4 0 0 0 4 11.815V19a2 2 0 1 0 4 0v-4a2 2 0 0 1 2-2z");
}

</style>
