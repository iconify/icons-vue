<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j-_4k_q9u"/><path class="h2t59vbki"/><path class="uzcia5bmm"/><path class="ck59p8blb"/><path class="cqnexabvb"/><path class="ea3ekee5h"/><path class="o-lyxcngp"/><path class="s6wepcb6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:compensate-duotone-regular" /></template>
<style>
.ck59p8blb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 13.5 4.5 16 7 18.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cqnexabvb {
  d: path("M4 8h13");
}

.ea3ekee5h {
  d: path("M17 5.5 19.5 8 17 10.5");
}

.h2t59vbki {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 5.5 19.5 8 17 10.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j-_4k_q9u {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 8h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o-lyxcngp {
  d: path("M7 16h13");
}

.s6wepcb6n {
  d: path("M7 13.5 4.5 16 7 18.5");
}

.uzcia5bmm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 16h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
