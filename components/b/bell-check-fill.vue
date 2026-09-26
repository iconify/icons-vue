<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qperobbfd"/><path class="kpao5obta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-check-fill" /></template>
<style>
.kpao5obta {
  d: path("M8.2679 20C8.6252 20.6188 9.2855 21 10 21C10.7145 21 11.3748 20.6188 11.7321 20M16 5L18 7L22 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qperobbfd {
  fill: currentColor;
  d: path("M10 2C10.8534 2 11.6651 2.1781 12.4 2.4993C12.7645 2.6583 13 3.0183 13 3.416L13 8.4199C13 9.8449 14.1551 11 15.5801 11C16.0067 11 16.3864 11.2706 16.5255 11.6739C16.784 12.4235 17.092 12.9372 17.3624 13.3753C17.5707 13.7127 18 14.3239 18 15C18 16.1046 17.1046 17 16 17L4 17C2.8954 17 2 16.1046 2 15C2 14.4387 2.2784 13.9674 2.455 13.673C2.6689 13.3166 2.8785 13.007 3.1056 12.5528C3.5331 11.6977 4 10.3517 4 8C4 4.6863 6.6863 2 10 2Z");
  stroke: none;
}

</style>
