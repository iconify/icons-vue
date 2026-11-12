<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h5nl8ib0a"/><path class="p87jq6bic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gem-duocolor" /></template>
<style>
.h5nl8ib0a {
  stroke-opacity: 0.4;
  d: path("m8 9l2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p87jq6bic {
  d: path("m16.5 14l-3.831 4.257a.9.9 0 0 1-1.338 0L3.635 9.705A1 1 0 0 1 3.67 8.33l2.743-2.743A2 2 0 0 1 7.828 5h8.344a2 2 0 0 1 1.414.586l2.743 2.743a1 1 0 0 1 .036 1.376z");
}

</style>
