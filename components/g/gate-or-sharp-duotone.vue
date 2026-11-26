<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="d6i0qbc2r"/><path class="wfnj32itj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gate-or-sharp-duotone" /></template>
<style>
.d6i0qbc2r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.5094 17.6589C11.3887 18.9045 8.9348 19.6719 6.1133 19.9936C6.0757 19.9979 6.0378 20 6 20C5.4477 20 5 19.5523 5 19C5 18.8632 5.0281 18.7279 5.0824 18.6024C6.4505 15.4453 7 13.7201 7 12C7 10.2799 6.4505 8.5547 5.0824 5.3976C5.0281 5.2721 5 5.1368 5 5C5 4.4477 5.4477 4 6 4C6.0378 4 6.0757 4.0021 6.1133 4.0064C11.7959 4.6543 15.9148 7.1059 18.8299 11.4421C18.9408 11.607 19 11.8013 19 12C19 12.1987 18.9408 12.393 18.8299 12.5579C17.3853 14.7068 15.6323 16.4119 13.5094 17.6589Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wfnj32itj {
  d: path("M1 8L7.2031 8M1 16L7.2031 16M18 12L23 12");
}

</style>
