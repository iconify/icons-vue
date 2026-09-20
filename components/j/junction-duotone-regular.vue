<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oqb-zyedx"/><path class="es_kn7b1m"/><path class="q9b8ckb8y"/><path class="qwkyr8b0i"/><path class="vfsuav3gb"/><path class="o7mb9vbwf"/><path class="x_6spmb5u"/><path class="cfwe2fbcx"/><path class="gaonsmbbz"/><path class="v3qgglbcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:junction-duotone-regular" /></template>
<style>
.cfwe2fbcx {
  d: path("M8 22v-6H2");
}

.es_kn7b1m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 2v6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gaonsmbbz {
  d: path("M16 22v-6h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o7mb9vbwf {
  d: path("M8 2v6H2");
}

.oqb-zyedx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 2v6H2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q9b8ckb8y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 22v-6H2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qwkyr8b0i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 22v-6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v3qgglbcl {
  d: path("M12 9.5v5");
}

.vfsuav3gb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 9.5v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x_6spmb5u {
  d: path("M16 2v6h6");
}

</style>
