<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nb2_g4mqj"/><path class="lnwwady7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-rain-wind-two-tone" /></template>
<style>
.lnwwady7b {
  d: path("M8.5 17L6.5 21M13 17L11 21M17.5 17L15.5 21");
}

.nb2_g4mqj {
  stroke-opacity: 0.4;
  d: path("M4 16.464C2.762 15.75 2 14.429 2 13C2 10.791 3.791 9 6 9C6 5.686 8.686 3 12 3C15.314 3 18 5.686 18 9C20.209 9 22 10.791 22 13C22 13.823 21.747 14.61 21.296 15.267");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
