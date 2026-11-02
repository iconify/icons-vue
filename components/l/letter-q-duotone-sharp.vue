<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mylinobyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-q-duotone-sharp" /></template>
<style>
.mylinobyl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3a6 6 0 0 0-6 6v6a6 6 0 0 0 6 6m0-18a6 6 0 0 1 6 6v6a6 6 0 0 1-6 6m1-6l6 6");
}

</style>
