<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tsm_xmb_i"/><path class="z1kq20btb"/><path class="ibawpck_m"/><path class="o3rjf96zo"/><path class="zifm62gud"/><path class="q3srlnbfr"/><path class="mxzk029nb"/><path class="c438ceftc"/><path class="n96aj2bbi"/><path class="zpl29uvhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:border-crossing-duotone-thin" /></template>
<style>
.c438ceftc {
  d: path("M12 17v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ibawpck_m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 17v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mxzk029nb {
  d: path("M12 10v4");
}

.n96aj2bbi {
  d: path("M4 12h15");
}

.o3rjf96zo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q3srlnbfr {
  d: path("M12 2v5");
}

.tsm_xmb_i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 2v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z1kq20btb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 10v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zifm62gud {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zpl29uvhf {
  d: path("m16 9 3 3 -3 3");
}

</style>
