<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tnzrbcc1j"/><path class="xsb473bfi"/><path class="kuhn_7bnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-historian" /></template>
<style>
.kuhn_7bnb {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.2 2.3 2.2 5.5 2.5m5 6l2-3l2 1.5l2.5-3.5");
}

.tnzrbcc1j {
  d: path("M10.662 21.211C6.893 20.988 4 19.845 4 18.5v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v6.655");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xsb473bfi {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75c1.128 0 2.204-.082 3.18-.23m1.59-.32c1.087-.28 1.964-.653 2.528-1.082");
}

</style>
