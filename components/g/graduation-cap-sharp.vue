<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzp4sfoza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:graduation-cap-sharp" /></template>
<style>
.zzp4sfoza {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 6l8 4l-8 4l-8-4zm-4 6v4c0 1.105 1.79 2 4 2s4-.895 4-2v-4m4-2v5");
}

</style>
