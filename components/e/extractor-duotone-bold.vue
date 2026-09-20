<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ejftrqblz"/><path class="ifkmoki6m"/><path class="gm48cefra"/><path class="bgia9xbjb"/><path class="t_57glb-y"/><path class="o7xcj9b5m"/><path class="iu3j18b-o"/><path class="izkbhz86a"/><path class="cfyvl-o0i"/><path class="mi_m6achy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:extractor-duotone-bold" /></template>
<style>
.bgia9xbjb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cfyvl-o0i {
  d: path("M16 12h4");
}

.ejftrqblz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 2H6v19h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gm48cefra {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ifkmoki6m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iu3j18b-o {
  d: path("M9 8h4");
}

.izkbhz86a {
  d: path("M9 12h4");
}

.mi_m6achy {
  d: path("m17 9 3 3 -3 3");
}

.o7xcj9b5m {
  d: path("M13 2H6v19h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t_57glb-y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
