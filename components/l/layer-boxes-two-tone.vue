<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hfjpitb0i"/><path class="t_-z-lykf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layer-boxes-two-tone" /></template>
<style>
.hfjpitb0i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.124 1.202C11.677 0.933 12.323 0.933 12.876 1.202L21.876 5.59C22.624 5.954 23 6.681 23 7.388V15.987C23 17.134 22.345 18.182 21.314 18.685L12.876 22.798C12.323 23.067 11.677 23.067 11.124 22.798L2.685 18.685C1.654 18.182 1 17.134 1 15.987L1.005 7.529C0.953 6.779 1.323 5.98 2.123 5.59L11.124 1.202Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t_-z-lykf {
  d: path("M2 12.625L11.562 17.286C11.838 17.421 12.162 17.421 12.438 17.286L22 12.625M2.006 7.5L2 12.625V15.988C2 16.752 2.436 17.45 3.124 17.785L11.562 21.899C11.838 22.034 12.162 22.034 12.438 21.899L20.876 17.785C21.564 17.45 22 16.752 22 15.988V12.625M22 12.625V7.395M22 7.395C21.998 7.75 21.81 8.105 21.438 8.286L12.438 12.674C12.162 12.809 11.838 12.809 11.562 12.674L2.562 8.286C2.227 8.123 2.041 7.819 2.006 7.5C1.963 7.106 2.148 6.69 2.562 6.489L11.562 2.101C11.838 1.966 12.162 1.966 12.438 2.101L21.438 6.489C21.815 6.672 22.003 7.034 22 7.395Z");
}

</style>
