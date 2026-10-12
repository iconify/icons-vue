<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmohf4pgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ice-cubes-sharp" /></template>
<style>
.nmohf4pgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.49 13.05l4.52-.6l1.49-.2l.2 1.49l.6 4.52l.2 1.49l-1.49.2l-4.52.6l-1.49.2l-.2-1.49l-.6-4.52l-.2-1.49zm10.98-9.74l4.06.88L21 4.5l-.31 1.47l-.88 4.06l-.31 1.47l-1.47-.31l-4.06-.88L12.5 10l.31-1.47l.88-4.06L14 3z");
}

</style>
