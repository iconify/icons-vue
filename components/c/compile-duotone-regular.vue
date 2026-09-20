<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t02ms39nd"/><path class="log_y59fn"/><path class="e-gdovb4r"/><path class="p1-4htbpj"/><path class="e5d_yrbyo"/><path class="l5r0hwbum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:compile-duotone-regular" /></template>
<style>
.e-gdovb4r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 10 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e5d_yrbyo {
  d: path("M12 13h9");
}

.l5r0hwbum {
  d: path("m18 10 3 3 -3 3");
}

.log_y59fn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 13h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p1-4htbpj {
  d: path("m10 4 -6 6 6 6");
}

.t02ms39nd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 4 -6 6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
