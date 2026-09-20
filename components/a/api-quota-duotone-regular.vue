<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wywiukbgn"/><path class="ku_telleq"/><path class="uqjbcwbtx"/><path class="k3m1vd7mo"/><path class="mn03ngslq"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="li19mgbhm"/><path class="a-ogebbgz"/><path class="fl5-97bom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:api-quota-duotone-regular" /></template>
<style>
.a-ogebbgz {
  d: path("M12 7v9");
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.fl5-97bom {
  d: path("M15 12v4");
}

.k3m1vd7mo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ku_telleq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.li19mgbhm {
  d: path("M9 10v6");
}

.mn03ngslq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 12v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uqjbcwbtx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wywiukbgn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
