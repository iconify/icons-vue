<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i_gdb-bxp"/><path clip-rule="evenodd" class="rlq3bc5ub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-alert" /></template>
<style>
.i_gdb-bxp {
  d: path("M12 20H5C3.3432 20 2 18.657 2 17V7M2 7C2 5.343 3.3432 4 5 4H19C20.6569 4 22 5.343 22 7M2 7L11.2929 11C11.7154 11.282 12.2846 11.282 12.7071 11L22 7M22 7V10M19 14V16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rlq3bc5ub {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 20C20 20.552 19.5523 21 19 21C18.4477 21 18 20.552 18 20C18 19.448 18.4477 19 19 19C19.5523 19 20 19.448 20 20Z");
  stroke: none;
}

</style>
