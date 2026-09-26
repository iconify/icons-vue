<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="t0e2nkp4h"/><path class="v-gqv21cb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bike-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t0e2nkp4h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 17.5C23 19.9853 20.9853 22 18.5 22C16.0147 22 14 19.9853 14 17.5C14 15.0147 16.0147 13 18.5 13C20.9853 13 23 15.0147 23 17.5ZM10 17.5C10 19.9853 7.9853 22 5.5 22C3.0147 22 1 19.9853 1 17.5C1 15.0147 3.0147 13 5.5 13C7.9853 13 10 15.0147 10 17.5ZM19 4C19 5.1046 18.1046 6 17 6C15.8954 6 15 5.1046 15 4C15 2.8954 15.8954 2 17 2C18.1046 2 19 2.8954 19 4Z");
  stroke: none;
}

.v-gqv21cb {
  d: path("M18.5 21C20.433 21 22 19.433 22 17.5C22 15.567 20.433 14 18.5 14C16.567 14 15 15.567 15 17.5C15 19.433 16.567 21 18.5 21ZM5.5 21C7.433 21 9 19.433 9 17.5C9 15.567 7.433 14 5.5 14C3.567 14 2 15.567 2 17.5C2 19.433 3.567 21 5.5 21ZM17 5C17.5523 5 18 4.5523 18 4C18 3.4477 17.5523 3 17 3C16.4477 3 16 3.4477 16 4C16 4.5523 16.4477 5 17 5ZM11.8277 17.7858L12.8624 13.0671L9.0351 10.9545L14.4065 7.2897L16.0617 10.9109L19.4635 11.0352");
}

</style>
