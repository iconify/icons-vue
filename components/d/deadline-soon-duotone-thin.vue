<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tqek15bkw"/><path class="rr5s23bmj"/><path class="d1sql1bsn"/><path class="kff2247zx"/><path class="ed-nihbqg"/><path class="hk697hhuu"/><path class="yazo7scbq"/><path class="jms1xqp8l"/><path class="zknktnbra"/><path class="c5cbiniuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:deadline-soon-duotone-thin" /></template>
<style>
.c5cbiniuw {
  d: path("m9 17.5 3 -3 3 3");
}

.d1sql1bsn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 3h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ed-nihbqg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 17.5 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hk697hhuu {
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jms1xqp8l {
  d: path("M9 3h6");
}

.kff2247zx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 13.5 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rr5s23bmj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tqek15bkw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yazo7scbq {
  d: path("M12 3v3");
}

.zknktnbra {
  d: path("m9 13.5 3 -3 3 3");
}

</style>
