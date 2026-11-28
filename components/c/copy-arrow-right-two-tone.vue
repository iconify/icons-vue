<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lghy7zdvd"/><path class="zca2_bcyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-arrow-right-two-tone" /></template>
<style>
.lghy7zdvd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 7L19 7C21.2091 7 23 8.7909 23 11L23 19C23 21.2091 21.2091 23 19 23L11 23C8.7909 23 7 21.2091 7 19L7 11C7 8.7909 8.7909 7 11 7Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zca2_bcyh {
  d: path("M15.8284 4C15.4046 2.8015 14.2714 2 13 2H5C3.34315 2 2 3.34315 2 5V13C2 14.2714 2.8015 15.4046 4 15.8284M11 8H19C20.65684 8 22 9.34316 22 11V19C22 20.65684 20.65684 22 19 22H11C9.34316 22 8 20.65684 8 19V11C8 9.34316 9.34316 8 11 8ZM12 15L18 15M15 12L18 15L15 18");
}

</style>
