<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vcb5hd08r"/><path class="d5g74ftrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-pen-sharp-two-tone" /></template>
<style>
.d5g74ftrq {
  d: path("M9.2199 21L3 21L3 5L21 5L21 9.3202M6 11L14 11M8 2L8 8M16 2L16 8M20.4142 15.6329L16.1715 19.8755L12.2189 20.9998L13.3431 17.0471L17.5858 12.8044C17.9609 12.4294 18.4696 12.2186 19 12.2186C20.1046 12.2186 21 13.1141 21 14.2186C21 14.7491 20.7893 15.2578 20.4142 15.6329Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vcb5hd08r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.7573 14.2186L16.8787 12.0973C17.4413 11.5348 18.2043 11.2186 19 11.2186C20.6569 11.2186 22 12.5618 22 14.2186C22 15.0143 21.684 15.7774 21.1213 16.34L16.8786 20.5826C16.7582 20.7031 16.6089 20.7907 16.4451 20.8373L12.4925 21.9616C12.4035 21.987 12.3114 21.9998 12.2189 21.9998C11.6666 21.9998 11.2189 21.5521 11.2189 20.9998C11.2189 20.9073 11.2317 20.8152 11.257 20.7262L12.3812 16.7735C12.4278 16.6097 12.5155 16.4605 12.636 16.34Z");
  stroke: none;
}

</style>
