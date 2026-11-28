<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hulkn4bbv"/><path class="i-w726bqw"/><path class="co643xayb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:droplet-half-sharp-two-tone" /></template>
<style>
.co643xayb {
  fill: currentColor;
  d: path("M9.5093 6.2847L12 3.5L17.2175 9.3333C18.3654 10.6167 19 12.2782 19 14C19 17.866 15.866 21 12 21L12 7.618C12 7.0657 11.5523 6.618 11 6.618C10.7154 6.618 10.4444 6.7393 10.2546 6.9514Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hulkn4bbv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.9629 8.6666C19.2747 10.1334 20 12.0322 20 14C20 18.4183 16.4183 22 12 22C7.5817 22 4 18.4183 4 14C4 12.0322 4.7253 10.1334 6.0371 8.6666L12 1.9999L17.9629 8.6666Z");
  stroke: none;
}

.i-w726bqw {
  stroke-linejoin: miter;
  d: path("M17.2175 9.3333C18.3654 10.6167 19 12.2782 19 14C19 17.866 15.866 21 12 21C8.134 21 5 17.866 5 14C5 12.2782 5.6346 10.6167 6.7825 9.3333L12 3.5L17.2175 9.3333Z");
}

</style>
