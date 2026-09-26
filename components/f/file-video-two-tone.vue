<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xxcb1mbaj"/><path class="llhcjkbjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-video-two-tone" /></template>
<style>
.llhcjkbjk {
  d: path("M14 2H8C5.79086 2 4 3.79086 4 6V18C4 20.2091 5.79086 22 8 22H16C18.2091 22 20 20.2091 20 18V8L14 2ZM14 2V5C14 6.65685 15.3431 8 17 8H20M10.4472 12.1056L14.4472 14.1056C14.786 14.275 15 14.6212 15 15C15 15.3788 14.786 15.725 14.4472 15.8944L10.4472 17.8944C10.3084 17.9639 10.1552 18 10 18C9.4477 18 9 17.5523 9 17L9 13C9 12.4477 9.4477 12 10 12C10.1552 12 10.3084 12.0361 10.4472 12.1056Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xxcb1mbaj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 1C14.2652 1 14.5195 1.1054 14.707 1.293L20.707 7.293C20.8946 7.4805 21 7.7348 21 8V18C21 20.7614 18.7614 23 16 23H8C5.2386 23 3 20.7614 3 18V6C3 3.2386 5.2386 1 8 1H14Z");
  stroke: none;
}

</style>
