<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9dayxyvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flashlight-on-sharp" /></template>
<style>
.r9dayxyvn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 6l6 6l-4 4h-3l-5 5l-3-3l5-5v-3zM9 9l6 6m1-12v2m3 0l2-2m-2 5h2");
}

</style>
