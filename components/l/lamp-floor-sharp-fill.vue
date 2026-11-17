<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tvvfipj0a"/><path class="l9rjnbbpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lamp-floor-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l9rjnbbpe {
  d: path("M12 12V22M8 22H16");
}

.tvvfipj0a {
  fill: currentColor;
  d: path("M14 1C14.379 1 14.725 1.214 14.895 1.553L19.895 11.553C20.049 11.863 20.033 12.231 19.851 12.525C19.668 12.82 19.347 13 19 13H5C4.653 13 4.332 12.82 4.149 12.525C3.967 12.231 3.951 11.863 4.105 11.553L9.105 1.553L9.177 1.432C9.362 1.164 9.669 1 10 1H14Z");
  stroke: none;
}

</style>
