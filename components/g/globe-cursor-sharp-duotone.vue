<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gjthifbuo"/><path class="ppwi24bkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-cursor-sharp-duotone" /></template>
<style>
.gjthifbuo {
  stroke-opacity: 0.4;
  d: path("M12 22C6.4771 22 2 17.5228 2 12C2 6.4771 6.4771 2 12 2C17.5228 2 22 6.4771 22 12M2 12L22 12M12 2C14.6667 5 16 8.5 16 12M12 2C9.3333 5 8 8.5 8 12C8 15.5 9.3333 19 12 22");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ppwi24bkf {
  d: path("M17.9543 22L15.8719 15.8669L22 18.0514L19.4086 19.3063L17.9543 22Z");
}

</style>
