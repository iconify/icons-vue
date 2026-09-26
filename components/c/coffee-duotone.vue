<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fiqwvobaq"/><path clip-rule="evenodd" class="ypvgs-1rm"/><path class="vv3j1obhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:coffee-duotone" /></template>
<style>
.fiqwvobaq {
  stroke-opacity: 0.4;
  d: path("M16 13L17 13C18.6569 13 20 14.3431 20 16C20 17.6569 18.6569 19 17 19L16 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vv3j1obhc {
  d: path("M8.5 6C8.5 5.2131 8.8705 4.4721 9.5 4C10.1295 3.5279 10.5 2.7869 10.5 2M13.5 6C13.5 5.2131 13.8705 4.4721 14.5 4C15.1295 3.5279 15.5 2.7869 15.5 2");
}

.ypvgs-1rm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 10L15 10C16.1046 10 17 10.8954 17 12L17 19C17 21.2091 15.2091 23 13 23L7 23C4.7909 23 3 21.2091 3 19L3 12C3 10.8954 3.8954 10 5 10Z");
  stroke: none;
}

</style>
