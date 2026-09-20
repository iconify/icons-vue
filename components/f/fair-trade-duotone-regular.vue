<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uw099db1h"/><path class="hqs3z7wnn"/><path class="vnxwo0g3o"/><path class="yv2_ckbqx"/><path class="ilcfk6b1a"/><path class="r7xk8o29f"/><path class="k4qo1xe9v"/><path class="bai-ikdbm"/><path class="qorafhbcl"/><path class="qw7b_6b1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fair-trade-duotone-regular" /></template>
<style>
.bai-ikdbm {
  d: path("M9 6a3 3 0 0 1 -6 0");
}

.hqs3z7wnn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 6h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ilcfk6b1a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 20h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k4qo1xe9v {
  d: path("M4 6h16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qorafhbcl {
  d: path("M21 6a3 3 0 0 1 -6 0");
}

.qw7b_6b1t {
  d: path("M8 20h8");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.uw099db1h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vnxwo0g3o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 6a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yv2_ckbqx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 6a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
