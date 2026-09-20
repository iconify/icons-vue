<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ovuj95fue"/><path class="ez7_a9bzn"/><path class="ok0ix8bpo"/><path class="yjhohbbyr"/><path class="i6yllfq7b"/><path class="n_s7qxbob"/><path class="c4ap_p0of"/><path class="s2ui7wbye"/><path class="mfc7nxp-y"/><path class="du_3_4tit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gradient-clip-duotone-thin" /></template>
<style>
.c4ap_p0of {
  d: path("M12 4v15");
}

.du_3_4tit {
  d: path("M4 21.5h16");
}

.ez7_a9bzn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i6yllfq7b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 21.5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mfc7nxp-y {
  d: path("M9 7h6");
}

.n_s7qxbob {
  d: path("M6 10v9");
}

.ok0ix8bpo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ovuj95fue {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 10v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s2ui7wbye {
  d: path("M18 12v7");
}

.yjhohbbyr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
