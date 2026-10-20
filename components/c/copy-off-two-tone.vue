<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="aqeu16b9p"/><path class="crxs8-02p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-off-two-tone" /></template>
<style>
.aqeu16b9p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M21.8284 21.8284C21.0789 22.5794 20.0611 23.001 19 23L11 23C8.7909 23 7 21.2091 7 19L7 11C6.999 9.9389 7.4206 8.9211 8.1716 8.1716L21.8284 21.8284ZM12.9498 8.7071C12.7621 8.5196 12.6567 8.2651 12.6567 7.9998C12.6567 7.4475 13.1046 6.9998 13.6569 7L19 7C21.2091 7 23 8.7909 23 11L23 16.3431C23.0002 16.8954 22.5525 17.3433 22.0002 17.3433C21.7349 17.3433 21.4804 17.2379 21.2929 17.0502L12.9498 8.7071Z");
  stroke: none;
}

.crxs8-02p {
  d: path("M2.8787 2.8787C2.3358 3.4216 2 4.1716 2 5L2 13C2 14.2714 2.8015 15.4046 4 15.8284M21.1213 21.1213C20.5784 21.6642 19.8284 22 19 22L11 22C9.3432 22 8 20.6568 8 19L8 11C8 10.1716 8.3358 9.4216 8.8787 8.8787M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
