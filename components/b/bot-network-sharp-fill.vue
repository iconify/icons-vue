<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="guq3owbvi"/><path class="kdvxyveof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-network-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.guq3owbvi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 5C5 4.4477 5.4477 4 6 4L18 4C18.5523 4 19 4.4477 19 5L19 13C19 13.5523 18.5523 14 18 14L6 14C5.4477 14 5 13.5523 5 13ZM11 9C11 8.4477 10.5523 8 10 8C9.4477 8 9 8.4477 9 9C9 9.5523 9.4477 10 10 10C10.5523 10 11 9.5523 11 9ZM15 9C15 8.4477 14.5523 8 14 8C13.4477 8 13 8.4477 13 9C13 9.5523 13.4477 10 14 10C14.5523 10 15 9.5523 15 9ZM1 17C1 16.4477 1.4477 16 2 16L8 16C8.5523 16 9 16.4477 9 17L9 22C9 22.5523 8.5523 23 8 23L2 23C1.4477 23 1 22.5523 1 22ZM15 17C15 16.4477 15.4477 16 16 16L22 16C22.5523 16 23 16.4477 23 17L23 22C23 22.5523 22.5523 23 22 23L16 23C15.4477 23 15 22.5523 15 22Z");
  stroke: none;
}

.kdvxyveof {
  d: path("M12 5L12 1M3 9L6 9M18 9L21 9M9 13L5 17M15 13L19 17");
}

</style>
