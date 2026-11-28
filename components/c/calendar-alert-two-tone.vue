<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a1eygpb7o"/><path class="prqpes_nw"/><path clip-rule="evenodd" class="f-q89ibyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-alert-two-tone" /></template>
<style>
.a1eygpb7o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 4H18C20.209 4 22 5.791 22 8V11C22 11.552 21.552 12 21 12H15C13.343 12 12 13.343 12 15V21C12 21.552 11.552 22 11 22H6C3.791 22 2 20.209 2 18V8C2 5.791 3.791 4 6 4Z");
  stroke: none;
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

.prqpes_nw {
  d: path("M11 21H6C4.343 21 3 19.657 3 18V8C3 6.343 4.343 5 6 5H18C19.657 5 21 6.343 21 8V11M7 11H17M8 3V7M16 3V7M18 15V17");
}

</style>
