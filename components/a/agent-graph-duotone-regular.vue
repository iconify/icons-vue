<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t7scrr-5w"/><path class="p8iop6bwz"/><path class="lcuc7cckr"/><path class="kcuwe5zmx"/><path class="irq30kbuv"/><path class="yl5h8v9ec"/><path class="gfyw8vbbf"/><path class="d-v-f28sf"/><path class="c-xj8zban"/><path class="q1jaj6b2n"/><path class="chx4f6b7j"/><path class="y69n27oio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-graph-duotone-regular" /></template>
<style>
.c-xj8zban {
  d: path("M20 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.chx4f6b7j {
  d: path("m14 15 2 2");
}

.d-v-f28sf {
  d: path("M12 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.gfyw8vbbf {
  d: path("M7.69 2.37a4 4 0 1 1 -3.38 0");
}

.irq30kbuv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14 15 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kcuwe5zmx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.69 2.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lcuc7cckr {
  fill: currentColor;
  d: path("M16 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p8iop6bwz {
  fill: currentColor;
  d: path("M20 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q1jaj6b2n {
  d: path("M16 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.t7scrr-5w {
  fill: currentColor;
  d: path("M12 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y69n27oio {
  d: path("m20 15 -2 2");
}

.yl5h8v9ec {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m20 15 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
