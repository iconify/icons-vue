<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mkh6f026t"/><path class="dvdnlhq9o"/><path class="su0af3bza"/><path class="jbndh3bbp"/><path class="k6nj2fbya"/><path class="x50q_4bdr"/><path class="u1mon9cdo"/><path class="o_qgmvj5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:change-capture-duotone-regular" /></template>
<style>
.dvdnlhq9o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 10h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jbndh3bbp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m20 13 -3 3h2.5l-3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.o_qgmvj5j {
  d: path("m20 13 -3 3h2.5l-3 3");
}

.su0af3bza {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 15h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u1mon9cdo {
  d: path("M3 15h9");
}

.x50q_4bdr {
  d: path("M3 10h18");
}

</style>
