<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w6akctrde"/><path class="x2dc1dsim"/><path class="mf1nsbben"/><path class="zaep_nbcg"/><path class="e8db_cbso"/><path class="s_uvnuivb"/><path class="uhty14kih"/><path class="f50v0cimy"/><path class="v5d935don"/><path class="ef5tcc6_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fence-duotone-bold" /></template>
<style>
.e8db_cbso {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 16h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ef5tcc6_c {
  d: path("M4 16h14");
}

.f50v0cimy {
  d: path("M18 7v14");
}

.mf1nsbben {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s_uvnuivb {
  d: path("M4 7v14");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uhty14kih {
  d: path("M11 7v14");
}

.v5d935don {
  d: path("M4 11h14");
}

.w6akctrde {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x2dc1dsim {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zaep_nbcg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 11h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
