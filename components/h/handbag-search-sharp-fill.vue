<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="krqvfex7g"/><path class="ydo674bvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:handbag-search-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.krqvfex7g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 22L4 22C3.4477 22 3 21.5523 3 21L3 7C3 6.4477 3.4477 6 4 6L7.101 6C7.5762 3.672 9.624 2 12 2C14.376 2 16.4238 3.672 16.899 6L20 6C20.5523 6 21 6.4477 21 7L21 12L11 12L11 22ZM9.1716 6L14.8284 6C14.4046 4.8014 13.2713 4 12 4C10.7287 4 9.5954 4.8014 9.1716 6Z");
  stroke: none;
}

.ydo674bvp {
  d: path("M19 17.5C19 18.8807 17.8807 20 16.5 20C15.1193 20 14 18.8807 14 17.5C14 16.1193 15.1193 15 16.5 15C17.8807 15 19 16.1193 19 17.5ZM18.2678 19.2678L20.2929 21.2929");
}

</style>
