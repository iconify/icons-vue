<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mkh6f026t"/><path class="l8i_2qb9f"/><path class="vluxytb9r"/><path class="pga6n1bci"/><path class="k6nj2fbya"/><path class="rhp6fjekz"/><path class="a-768stfr"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:format-code-duotone-regular" /></template>
<style>
.a-768stfr {
  d: path("M8 15h13");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.l8i_2qb9f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 10h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mkh6f026t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pga6n1bci {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rhp6fjekz {
  d: path("M8 10h13");
}

.vluxytb9r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 15h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
