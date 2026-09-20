<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="o2_q6ob_n"/><path class="jxw6tfblv"/><path class="hrrcydb2l"/><path class="s3pek1juy"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="e71sokbbi"/><path class="sb7rl7wyu"/><path class="pt73j1ikv"/><path class="yo-0d--rc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-column-stacked-duotone-bold" /></template>
<style>
.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e71sokbbi {
  d: path("M9 12v8");
}

.hrrcydb2l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jxw6tfblv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 6v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o2_q6ob_n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.pt73j1ikv {
  d: path("M15 14v6");
}

.r3faxubne {
  d: path("M4 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s3pek1juy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 8v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sb7rl7wyu {
  d: path("M9 6v3");
}

.yo-0d--rc {
  d: path("M15 8v3");
}

</style>
