<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fyyp-1wbz"/><path class="ilwzz0b0l"/><path clip-rule="evenodd" class="ueq-_ykop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-search-two-tone" /></template>
<style>
.fyyp-1wbz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 2H6C3.791 2 2 3.791 2 6V18C2 20.209 3.791 22 6 22H18C20.209 22 22 20.209 22 18V13C22 12.448 21.552 12 21 12H15C13.343 12 12 10.657 12 9V3C12 2.448 11.552 2 11 2Z");
  stroke: none;
}

.ilwzz0b0l {
  d: path("M11 3H6C4.343 3 3 4.343 3 6V18M3 18C3 19.657 4.343 21 6 21H18C19.657 21 21 19.657 21 18V17M3 18L7.939 13.061C8.525 12.475 9.475 12.475 10.061 13.061L12.08 15.08C12.608 15.608 13.444 15.667 14.041 15.219L15.959 13.781C16.556 13.333 17.392 13.392 17.92 13.92L21 17M21 17V13M19.5 7.5L21 9M20 5.5C20 6.881 18.881 8 17.5 8C16.119 8 15 6.881 15 5.5C15 4.119 16.119 3 17.5 3C18.881 3 20 4.119 20 5.5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ueq-_ykop {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 7.5C9.5 8.328 8.828 9 8 9C7.172 9 6.5 8.328 6.5 7.5C6.5 6.672 7.172 6 8 6C8.828 6 9.5 6.672 9.5 7.5Z");
  stroke: none;
}

</style>
