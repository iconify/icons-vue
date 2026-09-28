<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fa4msypqn"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-play-off-sharp-fill" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.fa4msypqn {
  fill: currentColor;
  d: path("M19.7782 19.7782C17.7153 21.8411 14.9174 23 12 23C5.9249 23 1 18.0751 1 12C1 9.0826 2.1589 6.2847 4.2218 4.2218L7.9627 7.9627L7.9627 16.6987C7.9627 17.251 8.4104 17.6987 8.9627 17.6987C9.1501 17.6987 9.3338 17.646 9.4927 17.5467L14.449 14.449ZM6.3532 2.558C8.0038 1.5687 9.9355 1 12 1C18.0753 1 23 5.9247 23 12C23 14.0645 22.4313 15.9962 21.442 17.6468Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
