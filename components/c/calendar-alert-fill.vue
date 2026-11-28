<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="bvttvqcdy"/><path class="dacnplbop"/><path clip-rule="evenodd" class="f-q89ibyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-alert-fill" /></template>
<style>
.bvttvqcdy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 4H18C20.209 4 22 5.791 22 8V11C22 11.552 21.552 12 21 12H15C13.343 12 12 13.343 12 15V21C12 21.552 11.552 22 11 22H6C3.791 22 2 20.209 2 18V8C2 5.791 3.791 4 6 4ZM7 10C6.448 10 6 10.448 6 11C6 11.552 6.448 12 7 12H17C17.552 12 18 11.552 18 11C18 10.448 17.552 10 17 10H7Z");
  stroke: none;
}

.dacnplbop {
  d: path("M8 3V7M16 3V7M18 15V17");
}

.f-q89ibyd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 20C18.552 20 19 20.448 19 21C19 21.552 18.552 22 18 22C17.448 22 17 21.552 17 21C17 20.448 17.448 20 18 20Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
