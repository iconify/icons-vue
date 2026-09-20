<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="k8p0vfjci"/><path class="btx7jbe-f"/><path class="ypfqvv0we"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="axr3xwb0d"/><path class="o22a_hbrn"/><path class="imcgu8bye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:forecast-cash-duotone-regular" /></template>
<style>
.axr3xwb0d {
  d: path("m7 17 4 -4");
}

.btx7jbe-f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13 11 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.imcgu8bye {
  d: path("m17 7 2 -2");
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k8p0vfjci {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 17 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o22a_hbrn {
  d: path("m13 11 2 -2");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.ypfqvv0we {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 7 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
