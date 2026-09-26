<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uzg8zabul"/><path class="dacae6bpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-dashed-panel-duotone" /></template>
<style>
.dacae6bpv {
  d: path("M15.5 4L15.5 14M10 9L15.1314 3.4021C15.3296 3.1859 15.6704 3.1859 15.8686 3.4021L21 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uzg8zabul {
  stroke-opacity: 0.4;
  d: path("M10.5 21L13.5 21M3 13.5L3 10.5M7 3L6 3C4.3431 3 3 4.3431 3 6M3 18C3 19.6569 4.3431 21 6 21M21 17L21 18C21 19.6569 19.6569 21 18 21");
}

</style>
