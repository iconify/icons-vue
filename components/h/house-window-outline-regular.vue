<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p52nwacub"/><path class="vc1mckb3d"/><path class="a5tuk3h7e"/><path class="cjsg0ab2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:house-window-outline-regular" /></template>
<style>
.a5tuk3h7e {
  d: path("M4 10h16");
}

.cjsg0ab2y {
  d: path("M2 20h20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p52nwacub {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.vc1mckb3d {
  d: path("M12 3v14");
}

</style>
