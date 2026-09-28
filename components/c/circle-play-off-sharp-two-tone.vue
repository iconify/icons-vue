<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jx1yt2bna"/><path class="qjuuhmh3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-play-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jx1yt2bna {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.7782 19.7782C17.7153 21.8411 14.9174 23 12 23C5.9249 23 1 18.0751 1 12C1 9.0826 2.1589 6.2847 4.2218 4.2218ZM6.3532 2.558C8.0038 1.5687 9.9355 1 12 1C18.0753 1 23 5.9247 23 12C23 14.0645 22.4313 15.9962 21.442 17.6468Z");
  stroke: none;
}

.qjuuhmh3c {
  d: path("M19.0711 19.0711C17.2614 20.8807 14.7614 22 12 22C6.4772 22 2 17.5228 2 12C2 9.2386 3.1193 6.7386 4.9289 4.9289M8.9627 8.9627L8.9627 16.6987L13.7233 13.7233M1.7071 1.7071L22.2929 22.2929");
}

</style>
