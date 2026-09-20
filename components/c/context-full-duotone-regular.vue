<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pr37be5vj"/><path class="gzjf714fp"/><path class="d9nb1lnep"/><path class="irk9zbcmx"/><path class="vy7jk_b7v"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="y5k8b5bfa"/><path class="l517yxbln"/><path class="coi-np7dk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:context-full-duotone-regular" /></template>
<style>
.b4x_isbqv {
  d: path("M8 6H5v12h3");
}

.coi-np7dk {
  d: path("M15 9v6");
}

.d_6ujebpi {
  d: path("M16 6h3v12h-3");
}

.d9nb1lnep {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gzjf714fp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 6h3v12h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.irk9zbcmx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l517yxbln {
  d: path("M12 9v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pr37be5vj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 6H5v12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vy7jk_b7v {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y5k8b5bfa {
  d: path("M9 9v6");
}

</style>
