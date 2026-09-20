<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wtrvdjbhl"/><path class="w3bbx5beq"/><path class="y7ptsibvm"/><path class="o17tysj-y"/><path class="g9ge-3btc"/><path class="znimqt98n"/><path class="mqbr2yyal"/><path class="ehnvkinxp"/><path class="i2-ny_bzf"/><path class="rsinobb0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hand-wash-duotone-regular" /></template>
<style>
.ehnvkinxp {
  d: path("M7 4v4");
}

.g9ge-3btc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i2-ny_bzf {
  d: path("M12 3v4");
}

.mqbr2yyal {
  d: path("M19 21v-6a2 2 0 0 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o17tysj-y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rsinobb0c {
  d: path("M17 4v4");
}

.w3bbx5beq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 21v-6a2 2 0 0 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wtrvdjbhl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 21v-6a2 2 0 0 1 4 0v-3a2 2 0 0 1 4 0v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y7ptsibvm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.znimqt98n {
  d: path("M5 21v-6a2 2 0 0 1 4 0v-3a2 2 0 0 1 4 0v4");
}

</style>
