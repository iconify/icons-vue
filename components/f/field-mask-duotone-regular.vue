<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wywiukbgn"/><path class="ku_telleq"/><path class="xi733_bbw"/><path class="lk97rhbbb"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="ji_wj2bhp"/><path class="rrzohjbez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:field-mask-duotone-regular" /></template>
<style>
.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.ji_wj2bhp {
  d: path("m9 9 3 3 3 -3");
}

.ku_telleq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.lk97rhbbb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 12v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rrzohjbez {
  d: path("M12 12v3");
}

.wywiukbgn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xi733_bbw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 9 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
