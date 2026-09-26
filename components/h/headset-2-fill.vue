<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yywrz0ino"/><path class="insy35blj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headset-2-fill" /></template>
<style>
.insy35blj {
  d: path("M4 10C4 5.581722 7.581722 2 12 2C16.418278 2 20 5.581722 20 10M18 17C18 19.209139 16.209139 21 14 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yywrz0ino {
  fill: currentColor;
  d: path("M3 10C3 8.343146 4.343146 7 6 7L6 7C7.656854 7 9 8.343146 9 10L9 15C9 16.656854 7.656854 18 6 18L6 18C4.343146 18 3 16.656854 3 15ZM15 10C15 8.343146 16.343146 7 18 7L18 7C19.656854 7 21 8.343146 21 10L21 15C21 16.656854 19.656854 18 18 18L18 18C16.343146 18 15 16.656854 15 15ZM9 21C9 19.895431 9.895431 19 11 19L13 19C14.104569 19 15 19.895431 15 21L15 21C15 22.104569 14.104569 23 13 23L11 23C9.895431 23 9 22.104569 9 21Z");
  stroke: none;
}

</style>
