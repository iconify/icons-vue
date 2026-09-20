<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="bpkly5byq"/><path class="r4p6spbhw"/><path class="fc669cbyx"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="f-mjnibpi"/><path class="w6105m-jv"/><path class="nwor_i7ms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-bar-horizontal-duotone-bold" /></template>
<style>
.bpkly5byq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 7h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f-mjnibpi {
  d: path("M4 7h12");
}

.fc669cbyx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 17h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nwor_i7ms {
  d: path("M4 17h14");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.r4p6spbhw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w6105m-jv {
  d: path("M4 12h8");
}

</style>
