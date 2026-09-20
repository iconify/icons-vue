<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d6389d2wr"/><path class="mibl8ybfa"/><path class="ohaw43bvl"/><path class="qp0zyybio"/><path class="ozpoglbbx"/><path class="wv9ug2bbl"/><path class="o8od38cnm"/><path class="juq6zh-od"/><path class="qq2awqbbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:currency-exchange-duotone-regular" /></template>
<style>
.d6389d2wr {
  fill: currentColor;
  d: path("M2.5 8a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.juq6zh-od {
  d: path("M6.5 15.5 4 18l2.5 2.5");
}

.mibl8ybfa {
  fill: currentColor;
  d: path("M12.5 8a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
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

.o8od38cnm {
  d: path("M4 18h16");
}

.ohaw43bvl {
  d: path("M2.5 8a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.ozpoglbbx {
  d: path("M12.5 8a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.qp0zyybio {
  d: path("M7 5.5v5");
}

.qq2awqbbs {
  d: path("M17.5 15.5 20 18l-2.5 2.5");
}

.wv9ug2bbl {
  d: path("M17 5.5v5");
}

</style>
