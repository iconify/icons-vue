<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg9hcx_kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cricket-bat-sharp" /></template>
<style>
.gg9hcx_kk {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2.449 17.1565C2.05789 17.5477 1.9143 18.1543 2.04979 18.8428C2.33196 20.2769 3.72313 21.668 5.15716 21.9502C5.84574 22.0857 6.45233 21.9421 6.84347 21.551L15.6721 12.7224L15.3183 8.6818L11.2776 8.328ZM9.8217 9.7839L9.8217 14.1783L14.2161 14.1783M15.3183 8.6818L22 2L22.2929 1.7071M20.5 18.5C20.5 19.6046 19.6046 20.5 18.5 20.5C17.3954 20.5 16.5 19.6046 16.5 18.5C16.5 17.3954 17.3954 16.5 18.5 16.5C19.6046 16.5 20.5 17.3954 20.5 18.5Z");
}

</style>
