<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n06idv60v"/><path class="l-8p2os5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:armchair-two-tone" /></template>
<style>
.l-8p2os5z {
  d: path("M4 11C2.8954 11 2 11.8954 2 13V17C2 18.6569 3.3431 20 5 20M4 11C5.1046 11 6 11.8954 6 13V13.5C6 13.7761 6.2239 14 6.5 14H17.5C17.7761 14 18 13.7761 18 13.5V13C18 11.8954 18.8954 11 20 11M4 11V7C4 4.2386 6.2386 2 9 2H15C17.7614 2 20 4.2386 20 7V11M20 11C21.1046 11 22 11.8954 22 13V17C22 18.6569 20.6569 20 19 20M19 20H5M19 20V22M5 20V22");
}

.n06idv60v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 10.1707L3 7C3 3.6863 5.6863 1 9 1L15 1C18.3137 1 21 3.6863 21 7L21 10.1707C22.1652 10.5825 23 11.6937 23 13L23 17C23 19.2092 21.2092 21 19 21L12 21L5 21C2.7908 21 1 19.2092 1 17L1 13C1 11.6937 1.8348 10.5825 3 10.1707Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
