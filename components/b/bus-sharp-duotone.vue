<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bttun-b7q"/><path clip-rule="evenodd" class="ja1pl769p"/><path class="dexqwyboi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bus-sharp-duotone" /></template>
<style>
.bttun-b7q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 19L2 19C1.4477 19 1 18.5523 1 18L1 4C1 3.4477 1.4477 3 2 3L17.964 3C18.1565 3 18.3449 3.0556 18.5066 3.16C21.308 4.9695 23 8.0768 23 11.4118L23 18C23 18.5523 22.5523 19 22 19L5 19Z");
  stroke: none;
}

.dexqwyboi {
  d: path("M9 18C9 19.1046 8.1046 20 7 20C5.8954 20 5 19.1046 5 18C5 16.8954 5.8954 16 7 16C8.1046 16 9 16.8954 9 18ZM19 18C19 19.1046 18.1046 20 17 20C15.8954 20 15 19.1046 15 18C15 16.8954 15.8954 16 17 16C18.1046 16 19 16.8954 19 18Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ja1pl769p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 5L13 5L13 8L9 8L9 5ZM15 5L17.6595 5C19.634 6.3806 20.8623 8.594 20.9892 11L17.4142 11L15 8.5858L15 5ZM7 8L3 8L3 5L7 5L7 8Z");
  stroke: none;
}

</style>
