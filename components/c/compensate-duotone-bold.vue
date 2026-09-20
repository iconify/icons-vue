<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bk9n2mkie"/><path class="i_btgdcac"/><path class="poujd5gcq"/><path class="dwo560-ck"/><path class="cqnexabvb"/><path class="ea3ekee5h"/><path class="o-lyxcngp"/><path class="s6wepcb6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:compensate-duotone-bold" /></template>
<style>
.bk9n2mkie {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 8h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cqnexabvb {
  d: path("M4 8h13");
}

.dwo560-ck {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 13.5 4.5 16 7 18.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ea3ekee5h {
  d: path("M17 5.5 19.5 8 17 10.5");
}

.i_btgdcac {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 5.5 19.5 8 17 10.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o-lyxcngp {
  d: path("M7 16h13");
}

.poujd5gcq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 16h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s6wepcb6n {
  d: path("M7 13.5 4.5 16 7 18.5");
}

</style>
