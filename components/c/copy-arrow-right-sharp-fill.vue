<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kytdc0isv"/><path clip-rule="evenodd" class="kykkd5t2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-arrow-right-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kykkd5t2k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 7L22 7C22.5523 7 23 7.4477 23 8L23 22C23 22.5523 22.5523 23 22 23L8 23C7.4477 23 7 22.5523 7 22L7 8C7 7.4477 7.4477 7 8 7ZM15.5858 16L14 17.5858L15.4142 19L18.7071 15.7071C19.0976 15.3166 19.0976 14.6834 18.7071 14.2929L15.4142 11L14 12.4142L15.5858 14L11 14L11 16Z");
  stroke: none;
}

.kytdc0isv {
  d: path("M15.8284 5L15.8284 2L2 2L2 15.8284L5 15.8284");
}

</style>
