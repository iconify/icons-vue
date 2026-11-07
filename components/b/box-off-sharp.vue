<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxogws90u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-off-sharp" /></template>
<style>
.uxogws90u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.636 5.636L3 6.444v11.112L12 22l6.025-2.975M8.423 3.766L12 2l9 4.444v9.9m-18-9.9L7.83 8.83M12 13v9m2.374-12.283L21 6.444M2 3l19 19");
}

</style>
