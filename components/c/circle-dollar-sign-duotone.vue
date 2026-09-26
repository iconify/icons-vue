<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g2u3clbzs"/><path class="z15tx_4tv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-dollar-sign-duotone" /></template>
<style>
.g2u3clbzs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C18.0753 1 23 5.9247 23 12C23 18.0753 18.0753 23 12 23C5.9247 23 1 18.0753 1 12C1 5.9247 5.9247 1 12 1Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z15tx_4tv {
  d: path("M12 6L12 18M14.5 7L10.5 7C9.1193 7 8 8.1193 8 9.5C8 10.8807 9.1193 12 10.5 12L13.5 12C14.8807 12 16 13.1193 16 14.5C16 15.8807 14.8807 17 13.5 17L9.5 17");
}

</style>
