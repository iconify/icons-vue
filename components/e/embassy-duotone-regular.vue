<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zjx2enbvg"/><path class="lbkuffism"/><path class="g_gub5-iy"/><path class="u36gbdq8a"/><path class="ef2afnbgy"/><path class="oqfv9rb9x"/><path class="yvwbi-etd"/><path class="lmoarbbkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:embassy-duotone-regular" /></template>
<style>
.ef2afnbgy {
  d: path("M4 21V10h16v11");
}

.g_gub5-iy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 2v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lbkuffism {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lmoarbbkf {
  d: path("M12 3h7v4h-7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.u36gbdq8a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3h7v4h-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yvwbi-etd {
  d: path("M12 2v8");
}

.zjx2enbvg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 21V10h16v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
