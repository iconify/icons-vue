<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1c8sddwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:helicopter-front" /></template>
<style>
.s1c8sddwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 13a6 6 0 1 1 12 0v2a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2zm2 4v4m8-4v4M6 21h4m4 0h4M6 13h12M3 3h18m-9 0v4");
}

</style>
