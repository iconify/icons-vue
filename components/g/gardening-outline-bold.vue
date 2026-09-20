<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kf-dg5j1v"/><path class="s09hy0b0y"/><path class="rx24zrjxq"/><path class="acx2mjbnt"/><path class="ftrg70bds"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gardening-outline-bold" /></template>
<style>
.acx2mjbnt {
  d: path("M12 11v6");
}

.ftrg70bds {
  d: path("M17 11v6");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.kf-dg5j1v {
  d: path("M12 2v9");
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

</style>
