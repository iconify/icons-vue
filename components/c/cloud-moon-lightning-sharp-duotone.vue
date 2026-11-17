<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l1s7kvbwq"/><path class="g0obvfn1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-moon-lightning-sharp-duotone" /></template>
<style>
.g0obvfn1t {
  d: path("M4.016 13.226L3.719 12.904C2.614 11.704 2 10.132 2 8.5C2 4.91 4.91 2 8.5 2C7.844 2.82 7.487 3.839 7.487 4.889C7.487 5.747 7.725 6.588 8.176 7.318L8.469 7.793M15.798 17.169L13.25 20H16.25L13.716 22.253");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l1s7kvbwq {
  stroke-opacity: 0.4;
  d: path("M9 18.887L8.5 18.598C7.572 18.062 7 17.072 7 16C7 14.343 8.343 13 10 13C10 10.515 12.015 8.5 14.5 8.5C16.985 8.5 19 10.515 19 13C20.657 13 22 14.343 22 16C22 17.072 21.428 18.062 20.5 18.598L20 18.887");
}

</style>
