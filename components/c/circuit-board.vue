<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zhyiu156y"/><path clip-rule="evenodd" class="ozlzr19zg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circuit-board" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ozlzr19zg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 18C15 18.552 14.5523 19 14 19C13.4477 19 13 18.552 13 18C13 17.448 13.4477 17 14 17C14.5523 17 15 17.448 15 18Z");
  stroke: none;
}

.zhyiu156y {
  d: path("M18 7H22M18 12H22M18 17H22M6 18H10M5 2H15C16.6569 2 18 3.343 18 5V19C18 20.657 16.6569 22 15 22H5C3.3431 22 2 20.657 2 19V5C2 3.343 3.3431 2 5 2ZM7 6H13C13.5523 6 14 6.448 14 7V12C14 12.552 13.5523 13 13 13H7C6.4477 13 6 12.552 6 12V7C6 6.448 6.4477 6 7 6Z");
}

</style>
