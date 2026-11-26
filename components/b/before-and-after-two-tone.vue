<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wbt28oomz"/><path class="q7u8x-byv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:before-and-after-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q7u8x-byv {
  d: path("M12 2V5M12 5V19M12 5H19C20.6569 5 22 6.3431 22 8V16C22 17.6569 20.6569 19 19 19H12M12 19V22M8 19H5C3.3431 19 2 17.6569 2 16V8C2 6.3431 3.3431 5 5 5H8");
}

.wbt28oomz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 12L11 19C11 19.5523 11.4477 20 12 20L19 20C21.2092 20 23 18.2092 23 16L23 8C23 5.7908 21.2092 4 19 4L12 4C11.4477 4 11 4.4477 11 5Z");
  stroke: none;
}

</style>
