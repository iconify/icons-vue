<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="g9sn7gnrs"/><path class="qhqq588lg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gift-sharp-fill" /></template>
<style>
.g9sn7gnrs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 6L22 6C22.5523 6 23 6.4477 23 7L23 10C23 11.1046 22.1046 12 21 12L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 12C1.8954 12 1 11.1046 1 10L1 7C1 6.4477 1.4477 6 2 6ZM3 8L21 8L21 10L3 10L3 8Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qhqq588lg {
  d: path("M12 7C9 7 7 6 7 4.5C7 3.1193 8.1193 2 9.5 2C11.5 2 12 5 12 7ZM12 7C15 7 17 6 17 4.5C17 3.1193 15.8807 2 14.5 2C12.5 2 12 5 12 7Z");
}

</style>
