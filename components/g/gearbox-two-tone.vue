<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fl45jebpr"/><path class="l_t0g4bib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gearbox-two-tone" /></template>
<style>
.fl45jebpr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.828 7.828C14.106 8.551 13.104 9 12 9C9.791 9 8 7.209 8 5C8 2.791 9.791 1 12 1C14.209 1 16 2.791 16 5C16 6.104 15.551 7.106 14.828 7.828Z");
  stroke: none;
}

.l_t0g4bib {
  d: path("M4 2V12M4 12V22M4 12H12M20 2V12M20 12V22M20 12H12M12 8V12M12 8C13.657 8 15 6.657 15 5C15 3.343 13.657 2 12 2C10.343 2 9 3.343 9 5C9 6.657 10.343 8 12 8ZM12 12V22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
