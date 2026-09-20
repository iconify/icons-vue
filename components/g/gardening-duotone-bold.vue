<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pwvno_5rq"/><path class="c9rn6abot"/><path class="icu4yobjx"/><path class="aq7-esb_r"/><path class="ysqks-b_k"/><path class="hpm6v1-ys"/><path class="kf-dg5j1v"/><path class="s09hy0b0y"/><path class="rx24zrjxq"/><path class="acx2mjbnt"/><path class="ftrg70bds"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gardening-duotone-bold" /></template>
<style>
.acx2mjbnt {
  d: path("M12 11v6");
}

.aq7-esb_r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c9rn6abot {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 11h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ftrg70bds {
  d: path("M17 11v6");
}

.hpm6v1-ys {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.icu4yobjx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.kf-dg5j1v {
  d: path("M12 2v9");
}

.pwvno_5rq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 2v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rx24zrjxq {
  d: path("M7 11v6");
}

.s09hy0b0y {
  d: path("M7 11h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ysqks-b_k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
