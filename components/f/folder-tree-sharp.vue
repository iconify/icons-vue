<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x21x-1rzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-tree-sharp" /></template>
<style>
.x21x-1rzl {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 2L3 19L10 19M3 5L3 8L10 8M13 3L16 3L17 5L21 5L21 10L13 10L13 3ZM13 14L16 14L17 16L21 16L21 21L13 21L13 14Z");
}

</style>
