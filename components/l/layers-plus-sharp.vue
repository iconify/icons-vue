<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzqgy1als"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-plus-sharp" /></template>
<style>
.wzqgy1als {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2L22 7.5L12 13L2 7.5ZM1.4819 11.7151L12.2251 17.6238M1.4819 16.2151L12.2251 22.1238M19 15L19 23M15 19L23 19");
}

</style>
