<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oqes2abxf"/><path class="vr0d5fbxi"/><path class="mjd3bubhw"/><path class="vqp2oy3do"/><path class="v9l_7xbhq"/><path class="nbib5l08z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:book-open-duotone-bold" /></template>
<style>
.mjd3bubhw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nbib5l08z {
  d: path("M12 7v14");
}

.oqes2abxf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7Q9 4 3 4v14q6 0 9 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v9l_7xbhq {
  d: path("M12 7q3 -3 9 -3v14q-6 0 -9 3");
}

.vqp2oy3do {
  d: path("M12 7Q9 4 3 4v14q6 0 9 3");
}

.vr0d5fbxi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7q3 -3 9 -3v14q-6 0 -9 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
