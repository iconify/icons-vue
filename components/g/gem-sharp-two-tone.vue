<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wgvwpxboh"/><path class="ifpc5fblc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gem-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ifpc5fblc {
  d: path("M7.5 3L16.5 3L21.9989 10.4793L12 20.9984L2.0011 10.4793ZM2.048 10.4164L21.952 10.4164M7.4845 3.0179L12 10.4164L16.5155 3.0179");
}

.wgvwpxboh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.7243 16.4278L12.7248 21.6874C12.536 21.886 12.274 21.9984 12 21.9984C11.726 21.9984 11.464 21.886 11.2752 21.6874L1.2763 11.1683C1.0996 10.9824 1.0011 10.7357 1.0011 10.4793C1.0011 10.2662 1.0692 10.0587 1.1954 9.887L6.6943 2.4077C6.8828 2.1514 7.1819 2 7.5 2L16.5 2C16.8181 2 17.1172 2.1514 17.3057 2.4077L22.8046 9.887C22.9308 10.0587 22.9989 10.2662 22.9989 10.4793C22.9989 10.7357 22.9004 10.9824 22.7237 11.1683Z");
  stroke: none;
}

</style>
