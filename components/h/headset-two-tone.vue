<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mkmw-5b4o"/><path class="eqxsdnbpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headset-two-tone" /></template>
<style>
.eqxsdnbpn {
  d: path("M4 10C4 8.895431 4.895431 8 6 8L6 8C7.104569 8 8 8.895431 8 10L8 16C8 17.104569 7.104569 18 6 18L6 18C4.895431 18 4 17.104569 4 16ZM16 10C16 8.895431 16.895431 8 18 8L18 8C19.104569 8 20 8.895431 20 10L20 16C20 17.104569 19.104569 18 18 18L18 18C16.895431 18 16 17.104569 16 16ZM4 10C4 5.581722 7.581722 2 12 2C16.418278 2 20 5.581722 20 10M18 18C18 20.209139 16.209139 22 14 22H12");
}

.mkmw-5b4o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 10C3 8.343146 4.343146 7 6 7L6 7C7.656854 7 9 8.343146 9 10L9 16C9 17.656854 7.656854 19 6 19L6 19C4.343146 19 3 17.656854 3 16ZM15 10C15 8.343146 16.343146 7 18 7L18 7C19.656854 7 21 8.343146 21 10L21 16C21 17.656854 19.656854 19 18 19L18 19C16.343146 19 15 17.656854 15 16Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
