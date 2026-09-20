<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="plw-owhdh"/><path class="yjc9h6oua"/><path class="cb-v5c5ba"/><path class="p5hd8ygud"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="strt8mboj"/><path class="p8yct170k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:keyword-search-duotone-bold" /></template>
<style>
.cb-v5c5ba {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.p5hd8ygud {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p8yct170k {
  d: path("M7 12h6");
}

.plw-owhdh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.strt8mboj {
  d: path("M7 8h6");
}

.yjc9h6oua {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
