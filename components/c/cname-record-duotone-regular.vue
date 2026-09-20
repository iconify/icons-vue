<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mkh6f026t"/><path class="uobmn7udv"/><path class="dd2oi04rr"/><path class="h17rb_vcn"/><path class="nze1kcl9o"/><path class="k6nj2fbya"/><path class="ae-e09b3w"/><path class="rkhcgsbdl"/><path class="zbpm1d36f"/><path class="hrjweb57d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cname-record-duotone-regular" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.dd2oi04rr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h17rb_vcn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 8 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hrjweb57d {
  d: path("m9 15 3 -3 3 3");
}

.k6nj2fbya {
  d: path("M3 5h18");
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

.nze1kcl9o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 15 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.uobmn7udv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zbpm1d36f {
  d: path("m9 8 3 -3 3 3");
}

</style>
