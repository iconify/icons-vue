<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qioqopbzb"/><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="w6y1evb0t"/><path class="azoavouow"/><path class="abeqv4uga"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="i-xxtdbfm"/><path class="b8iynqbad"/><path class="h4nnknbvo"/><path class="zw6iqebrn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:histogram-bucket-duotone-bold" /></template>
<style>
.abeqv4uga {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 13v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.azoavouow {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 8v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.b8iynqbad {
  d: path("M13 8v10");
}

.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h4nnknbvo {
  d: path("M17 13v5");
}

.i-xxtdbfm {
  d: path("M9 11v7");
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.qioqopbzb {
  fill: currentColor;
  d: path("M12 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
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

.w6y1evb0t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 11v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zw6iqebrn {
  d: path("M12 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
