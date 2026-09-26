<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t4y67fbcc"/><path class="fdk6ytbkq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-plus-duotone" /></template>
<style>
.fdk6ytbkq {
  d: path("M19 16V22M22 19H16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t4y67fbcc {
  stroke-opacity: 0.4;
  d: path("M12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12M2 12H22M12 2C14.6667 5 16 8.5 16 12M12 2C9.33333 5 8 8.5 8 12C8 15.5 9.33333 19 12 22");
}

</style>
