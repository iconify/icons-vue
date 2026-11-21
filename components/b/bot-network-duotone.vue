<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gzzndenrs"/><path class="pr30fbiow"/><path class="ml0jedc4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-network-duotone" /></template>
<style>
.gzzndenrs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 7C5 5.3431 6.3431 4 8 4L16 4C17.6569 4 19 5.3431 19 7L19 11C19 12.6569 17.6569 14 16 14L8 14C6.3431 14 5 12.6569 5 11Z");
  stroke: none;
}

.ml0jedc4u {
  fill: currentColor;
  d: path("M1 18C1 16.8954 1.8954 16 3 16L7 16C8.1046 16 9 16.8954 9 18L9 21C9 22.1046 8.1046 23 7 23L3 23C1.8954 23 1 22.1046 1 21ZM15 18C15 16.8954 15.8954 16 17 16L21 16C22.1046 16 23 16.8954 23 18L23 21C23 22.1046 22.1046 23 21 23L17 23C15.8954 23 15 22.1046 15 21ZM11 9C11 9.5523 10.5523 10 10 10C9.4477 10 9 9.5523 9 9C9 8.4477 9.4477 8 10 8C10.5523 8 11 8.4477 11 9ZM15 9C15 9.5523 14.5523 10 14 10C13.4477 10 13 9.5523 13 9C13 8.4477 13.4477 8 14 8C14.5523 8 15 8.4477 15 9Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pr30fbiow {
  d: path("M12 5V2M4 9H6M18 9H20M9 13L5 17M15 13L19 17");
}

</style>
