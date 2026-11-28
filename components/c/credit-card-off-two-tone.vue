<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kqgyvg15p"/><path class="skqfy9brk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-off-two-tone" /></template>
<style>
.kqgyvg15p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.646 20.646C20.144 20.874 19.587 21 19 21H5C2.791 21 1 19.209 1 17V7C1 5.378 1.966 3.981 3.353 3.353L20.646 20.646ZM21.293 17.05L8.95 4.707C8.769 4.526 8.657 4.276 8.657 4C8.657 3.448 9.105 3 9.657 3H19C21.209 3 23 4.791 23 7V16.343C23 16.895 22.552 17.343 22 17.343C21.724 17.343 21.474 17.231 21.293 17.05Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.skqfy9brk {
  d: path("M2 9H9M19.872 19.872C19.596 19.955 19.303 20 19 20H5C3.343 20 2 18.657 2 17V7C2 5.646 2.897 4.502 4.128 4.128M2 2L22 22");
}

</style>
