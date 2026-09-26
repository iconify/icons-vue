<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j9npc8b0b"/><path class="jb8hy8b-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eye-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j9npc8b0b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1.0244 11.7805C2.1537 6.7612 6.8552 3 12 3C17.1448 3 21.8463 6.7612 22.9756 11.7805C23.0081 11.925 23.0081 12.075 22.9756 12.2195C21.8463 17.2388 17.1448 21 12 21C6.8552 21 2.1537 17.2388 1.0244 12.2195C0.9919 12.075 0.9919 11.925 1.0244 11.7805Z");
  stroke: none;
}

.jb8hy8b-t {
  d: path("M15 12C15 13.6569 13.6569 15 12 15C10.3431 15 9 13.6569 9 12C9 10.3431 10.3431 9 12 9C13.6569 9 15 10.3431 15 12Z");
}

</style>
