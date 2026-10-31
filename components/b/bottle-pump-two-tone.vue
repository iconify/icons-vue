<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vgtv2obxr"/><path class="tvoh63bvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bottle-pump-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tvoh63bvg {
  d: path("M9 11L15 11C16.6569 11 18 12.3431 18 14L18 19C18 20.6569 16.6569 22 15 22L9 22C7.3431 22 6 20.6569 6 19L6 14C6 12.3431 7.3431 11 9 11ZM9 11L9 7.5C9 7.2239 9.2239 7 9.5 7L14.5 7C14.7761 7 15 7.2239 15 7.5L15 11M12 2L12 7M9 2L13.1716 2C14.9826 2 16.7194 2.7194 18 4");
}

.vgtv2obxr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 10.1263C17.7661 10.5827 18.9999 12.1759 19 14L19 19C19 21.2092 17.2092 23 15 23L9 23C6.7908 23 5 21.2092 5 19L5 14C5.0001 12.1759 6.2339 10.5827 8 10.1263L8 7.5C8 6.6716 8.6716 6 9.5 6L14.5 6C15.3284 6 16 6.6716 16 7.5L16 10.1263Z");
  stroke: none;
}

</style>
