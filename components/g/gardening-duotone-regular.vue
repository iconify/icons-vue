<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mm7rljbyg"/><path class="l_woid8eh"/><path class="jh2otjbvh"/><path class="sot87zl6h"/><path class="gxnpo3bcw"/><path class="pga6n1bci"/><path class="kf-dg5j1v"/><path class="s09hy0b0y"/><path class="rx24zrjxq"/><path class="acx2mjbnt"/><path class="ftrg70bds"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gardening-duotone-regular" /></template>
<style>
.acx2mjbnt {
  d: path("M12 11v6");
}

.ftrg70bds {
  d: path("M17 11v6");
}

.gxnpo3bcw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jh2otjbvh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.kf-dg5j1v {
  d: path("M12 2v9");
}

.l_woid8eh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 11h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mm7rljbyg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 2v9");
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

.rx24zrjxq {
  d: path("M7 11v6");
}

.s09hy0b0y {
  d: path("M7 11h10");
}

.sot87zl6h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
