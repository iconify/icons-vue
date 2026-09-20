<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qb21cnxrp"/><path class="yd_0eu7us"/><path class="moc63lp3w"/><path class="vqp2oy3do"/><path class="v9l_7xbhq"/><path class="nbib5l08z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:book-open-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.moc63lp3w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nbib5l08z {
  d: path("M12 7v14");
}

.qb21cnxrp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7Q9 4 3 4v14q6 0 9 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v9l_7xbhq {
  d: path("M12 7q3 -3 9 -3v14q-6 0 -9 3");
}

.vqp2oy3do {
  d: path("M12 7Q9 4 3 4v14q6 0 9 3");
}

.yd_0eu7us {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7q3 -3 9 -3v14q-6 0 -9 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
