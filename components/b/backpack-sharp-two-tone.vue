<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="avtudobdd"/><path class="yoh9sx1wm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:backpack-sharp-two-tone" /></template>
<style>
.avtudobdd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C14.209 1 16 2.791 16 5H20C20.552 5 21 5.448 21 6V22C21 22.552 20.552 23 20 23H4C3.448 23 3 22.552 3 22V6C3 5.448 3.448 5 4 5H8C8 2.791 9.791 1 12 1Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yoh9sx1wm {
  d: path("M4 15H20M9 10H15M8 15V19M15 6V5C15 3.343 13.657 2 12 2C10.343 2 9 3.343 9 5V6M4 22H20V6H4V22Z");
}

</style>
