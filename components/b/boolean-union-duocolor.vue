<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmhqoob3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-union-duocolor" /></template>
<style>
.tmhqoob3a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3h5a1 1 0 0 1 1 1v4a1 1 0 0 0 1 1h4a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H10a1 1 0 0 1-1-1v-4a1 1 0 0 0-1-1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1z");
}

</style>
