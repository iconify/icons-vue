<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kaypfub9l"/><path class="p_7q_ebuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-asterisk-two-tone" /></template>
<style>
.kaypfub9l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 3H19C21.209 3 23 4.791 23 7V10C23 10.552 22.552 11 22 11H16C14.343 11 13 12.343 13 14V20C13 20.552 12.552 21 12 21H5C2.791 21 1 19.209 1 17V7C1 4.791 2.791 3 5 3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p_7q_ebuw {
  d: path("M12 20H5C3.343 20 2 18.657 2 17V7M2 7C2 5.343 3.343 4 5 4H19C20.657 4 22 5.343 22 7M2 7L11.293 11C11.715 11.282 12.285 11.282 12.707 11L22 7M22 7V10M19 14V17M19 17V20M19 17L16.6 18.8M19 17L21.4 15.2M19 17L16.6 15.2M19 17L21.4 18.8");
}

</style>
