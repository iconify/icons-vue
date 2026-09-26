<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k8pnmpluo"/><path class="vya9v3a2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headset-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k8pnmpluo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 10C3 8.4812 4.4812 7 6 7L8 7C8.5523 7 9 7.4477 9 8L9 18C9 18.5523 8.5523 19 8 19L6 19C4.4812 19 3 17.5188 3 16L3 10ZM21 10C21 8.4812 19.5188 7 18 7L16 7C15.4477 7 15 7.4477 15 8L15 18C15 18.5523 15.4477 19 16 19L18 19C19.5188 19 21 17.5188 21 16L21 10Z");
  stroke: none;
}

.vya9v3a2h {
  d: path("M4 10C4 8.8954 4.8954 8 6 8L8 8L8 18L6 18C4.8954 18 4 17.1046 4 16L4 10ZM20 10C20 8.8954 19.1046 8 18 8L16 8L16 18L18 18C19.1046 18 20 17.1046 20 16L20 10ZM4 10C4 5.5817 7.5817 2 12 2C16.4183 2 20 5.5817 20 10M18 18L18 22L11 22");
}

</style>
