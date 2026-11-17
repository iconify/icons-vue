<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pw_gj_bct"/><path class="cm4xjk70o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-lightning-rain-two-tone" /></template>
<style>
.cm4xjk70o {
  d: path("M13.5 12L9 16.5H15L10.5 21M5 18.5V21M19 18.5V21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pw_gj_bct {
  stroke-opacity: 0.4;
  d: path("M2.536 15C2.185 14.392 2 13.702 2 13C2 10.791 3.791 9 6 9C6 5.686 8.686 3 12 3C15.314 3 18 5.686 18 9C20.209 9 22 10.791 22 13C22 13.702 21.815 14.392 21.464 15");
}

</style>
