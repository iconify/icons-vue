<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zkn3xyt6c"/><path class="my5268blj"/><path class="phi7aibzw"/><path class="aui1_r5dv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-heart-line-duotone" /></template>
<style>
.aui1_r5dv {
  d: path("M12 11.6913C13.35 10.3988 15 11.0235 15 12.6967C15 14.2766 12 16 12 16");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.my5268blj {
  d: path("M9.5 6H14.5C15.3284 6 16 5.32843 16 4.5V3.5C16 2.67157 15.3284 2 14.5 2H9.5C8.67157 2 8 2.67157 8 3.5V4.5C8 5.32843 8.67157 6 9.5 6Z");
}

.phi7aibzw {
  d: path("M12 16C12 16 9 14.2765 9 12.6967C9 11.0235 10.65 10.3988 12 11.6913");
}

.zkn3xyt6c {
  d: path("M16 4C18.175 4.01211 19.3529 4.10856 20.1213 4.87694C21 5.75562 21 7.16983 21 9.99826V15.9983C21 18.8267 21 20.2409 20.1213 21.1196C19.2426 21.9983 17.8284 21.9983 15 21.9983H9C6.17157 21.9983 4.75736 21.9983 3.87868 21.1196C3 20.2409 3 18.8267 3 15.9983V9.99826C3 7.16983 3 5.75562 3.87868 4.87694C4.64706 4.10856 5.82497 4.01211 8 4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
