<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="z4d_mjlxu"/><path class="xqdu5evlh"/><path class="hfkigjbqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-join-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hfkigjbqm {
  d: path("M12 16C13.6569 16 15 17.3431 15 19C15 20.6569 13.6569 22 12 22C10.3431 22 9 20.6569 9 19C9 17.3431 10.3431 16 12 16ZM5 2C6.6569 2 8 3.3432 8 5C8 6.6569 6.6569 8 5 8C3.3432 8 2 6.6569 2 5C2 3.3432 3.3432 2 5 2ZM19 2C20.6569 2 22 3.3432 22 5C22 6.6569 20.6569 8 19 8C17.3431 8 16 6.6569 16 5C16 3.3432 17.3431 2 19 2Z");
}

.xqdu5evlh {
  d: path("M12 16L12 11M5 8L5 11L19 11L19 8");
}

.z4d_mjlxu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 1C7.0711 1 9 2.929 9 5C9 7.0711 7.0711 9 5 9C2.929 9 1 7.0711 1 5C1 2.929 2.929 1 5 1ZM19 1C21.0711 1 23 2.929 23 5C23 7.0711 21.0711 9 19 9C16.9289 9 15 7.0711 15 5C15 2.929 16.9289 1 19 1ZM12 15C14.0711 15 16 16.9289 16 19C16 21.0711 14.0711 23 12 23C9.9289 23 8 21.0711 8 19C8 16.9289 9.9289 15 12 15Z");
  stroke: none;
}

</style>
