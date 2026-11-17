<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t-98w6bts"/><path class="x7tnbub6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-electric-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t-98w6bts {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.5234 3C16.1221 3 17.5671 3.9521 18.1982 5.4209L19.3066 8H20.5C21.0522 8.0001 21.5 8.4478 21.5 9C21.5 9.5081 21.1206 9.9264 20.6299 9.9902C21.4683 10.7227 22 11.7977 22 13V18.0342C22 19.6719 20.6719 21 19.0342 21C17.7599 20.9998 16.6386 20.1875 16.2305 19H7.7695C7.3614 20.1875 6.2401 20.9998 4.9658 21C3.3281 21 2 19.6719 2 18.0342V13C2 11.7983 2.5305 10.7228 3.3682 9.9902C2.8783 9.9256 2.5 9.5075 2.5 9C2.5 8.4477 2.9477 8 3.5 8H4.6924L5.8008 5.4209C6.4318 3.9521 7.8771 3.0002 9.4756 3H14.5234Z");
  stroke: none;
}

.x7tnbub6k {
  d: path("M13 8L10 11H14L11 14");
}

</style>
