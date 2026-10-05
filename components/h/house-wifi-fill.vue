<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a00nohhli"/><path class="f4ihe5fmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-wifi-fill" /></template>
<style>
.a00nohhli {
  d: path("M10 17.5359C10.6081 17.1848 11.2979 17 12 17C12.7021 17 13.3919 17.1848 14 17.5359M8 14.0718C9.2162 13.3697 10.5957 13 12 13C13.4043 13 14.7838 13.3697 16 14.0718M2 10.8473L10.7072 3.4703C11.4532 2.8383 12.5468 2.8383 13.2928 3.4703L22 10.8473M4 9.1528L4 19C4 20.1046 4.8954 21 6 21L8 21M16 21L18 21C19.1046 21 20 20.1046 20 19L20 9.1528");
}

.f4ihe5fmy {
  fill: currentColor;
  d: path("M13 21C13 21.5523 12.5523 22 12 22C11.4477 22 11 21.5523 11 21C11 20.4477 11.4477 20 12 20C12.5523 20 13 20.4477 13 21Z");
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
