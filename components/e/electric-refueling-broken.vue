<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="luoe06bir"/><path class="o85hb142l"/><path class="wu-2fgbxv"/><path class="aqrzy7b8m"/><path class="see2fgboo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:electric-refueling-broken" /></template>
<style>
.aqrzy7b8m {
  d: path("M19.5 4L20.7331 4.98647C20.8709 5.09673 20.9398 5.15186 21.0025 5.20805C21.5937 5.73807 21.9508 6.48086 21.9953 7.27364C22 7.35769 22 7.44594 22 7.62244V18.5C22 19.3284 21.3284 20 20.5 20C19.6716 20 19 19.3284 19 18.5V18.4286C19 17.6396 18.3604 17 17.5714 17H16");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.luoe06bir {
  d: path("M3 22V18M3 14V8C3 5.17157 3 3.75736 3.87868 2.87868C4.75736 2 6.17157 2 9 2H10C12.8284 2 14.2426 2 15.1213 2.87868C16 3.75736 16 5.17157 16 8V11M16 15V22");
}

.o85hb142l {
  stroke-linejoin: round;
  d: path("M9.5 10L8 12.5H11L9.5 15");
}

.see2fgboo {
  d: path("M22 8H20.5C19.6716 8 19 8.67157 19 9.5V11.9189C19 12.5645 19.4131 13.1377 20.0257 13.3419L22 14");
}

.wu-2fgbxv {
  d: path("M17 22H2");
}

</style>
