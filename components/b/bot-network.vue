<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oou1rgh6w"/><path class="f66c-0bag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-network" /></template>
<style>
.f66c-0bag {
  fill: currentColor;
  d: path("M11 9C11 9.5523 10.5523 10 10 10C9.4477 10 9 9.5523 9 9C9 8.4477 9.4477 8 10 8C10.5523 8 11 8.4477 11 9ZM15 9C15 9.5523 14.5523 10 14 10C13.4477 10 13 9.5523 13 9C13 8.4477 13.4477 8 14 8C14.5523 8 15 8.4477 15 9Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oou1rgh6w {
  d: path("M6 7C6 5.8954 6.8954 5 8 5L16 5C17.1046 5 18 5.8954 18 7L18 11C18 12.1046 17.1046 13 16 13L8 13C6.8954 13 6 12.1046 6 11ZM12 5V2M4 9H6M18 9H20M9 13L5 17M15 13L19 17M2 18C2 17.4477 2.4477 17 3 17L7 17C7.5523 17 8 17.4477 8 18L8 21C8 21.5523 7.5523 22 7 22L3 22C2.4477 22 2 21.5523 2 21ZM16 18C16 17.4477 16.4477 17 17 17L21 17C21.5523 17 22 17.4477 22 18L22 21C22 21.5523 21.5523 22 21 22L17 22C16.4477 22 16 21.5523 16 21Z");
}

</style>
