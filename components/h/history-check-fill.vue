<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r--s1i77g"/><path class="oihouwb2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:history-check-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oihouwb2n {
  d: path("M3.0469 3L6.0631 3.86C6.3287 3.94 6.4825 4.21 6.4068 4.48L5.5465 7.49");
}

.r--s1i77g {
  d: path("M12 22C6.4771 22 2 17.52 2 12C2 8.96 3.3577 6.23 5.5 4.4C5.6619 4.26 5.8284 4.13 5.999 4M22 12C22 6.48 17.5228 2 12 2C11.6625 2 11.3289 2.02 11 2.05M12 6V12H17M16 19L18 21L22 17");
}

</style>
