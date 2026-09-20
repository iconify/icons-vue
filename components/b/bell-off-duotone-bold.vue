<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yt70p9btb"/><path class="hpm6v1-ys"/><path class="ao2myme7y"/><path class="srzgk7jml"/><path class="jkuojibnm"/><path class="eo60n2g2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bell-off-duotone-bold" /></template>
<style>
.ao2myme7y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6.5 6.5 10 10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eo60n2g2k {
  d: path("m6.5 6.5 10 10");
}

.hpm6v1-ys {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.srzgk7jml {
  d: path("M3 17a9 9 0 0 1 18 0");
}

.yt70p9btb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
