<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b0nahy8lo"/><path class="rh0cep7rt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-left-dashed-panel-duotone" /></template>
<style>
.b0nahy8lo {
  stroke-opacity: 0.4;
  d: path("M10.5 3L13.5 3M21 10.5L21 13.5M3 7L3 6C3 4.3431 4.3431 3 6 3M18 3C19.6569 3 21 4.3431 21 6M17 21L18 21C19.6569 21 21 19.6569 21 18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rh0cep7rt {
  d: path("M4 15.5L14 15.5M9 10L3.4021 15.1314C3.1859 15.3296 3.1859 15.6704 3.4021 15.8686L9 21");
}

</style>
