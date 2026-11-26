<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p6-6k9g6g"/><path clip-rule="evenodd" class="inp5x62er"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-pen-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.inp5x62er {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 7.5C9.5 8.3284 8.8284 9 8 9C7.1716 9 6.5 8.3284 6.5 7.5C6.5 6.6716 7.1716 6 8 6C8.8284 6 9.5 6.6716 9.5 7.5ZM14.7573 14.2186L16.8787 12.0973C17.4413 11.5348 18.2043 11.2186 19 11.2186C20.6569 11.2186 22 12.5618 22 14.2186C22 15.0143 21.684 15.7774 21.1213 16.34L16.8786 20.5826C16.7582 20.7031 16.6089 20.7907 16.4451 20.8373L12.4925 21.9616C12.4035 21.987 12.3114 21.9998 12.2189 21.9998C11.6666 21.9998 11.2189 21.5521 11.2189 20.9998C11.2189 20.9073 11.2317 20.8152 11.257 20.7262L12.3812 16.7735C12.4278 16.6097 12.5155 16.4605 12.636 16.34Z");
  stroke: none;
}

.p6-6k9g6g {
  d: path("M9.3842 21L3 21L3 3L21 3L21 9.5614M3 18L9 12L11.5738 14.5738");
}

</style>
