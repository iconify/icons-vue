<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e6fmi8c4o"/><path class="donw2_baj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:letter-spacing-duotone" /></template>
<style>
.donw2_baj {
  d: path("M2 4V20M22 4V20");
}

.e6fmi8c4o {
  stroke-opacity: 0.4;
  d: path("M7 18L8.7857 13L11.0583 6.668C11.3743 5.783 12.6257 5.783 12.9417 6.668L15.2143 13L17 18M15.2143 13H8.7857");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
