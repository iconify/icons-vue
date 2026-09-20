<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n799wlg5y"/><path class="h93exbbfx"/><path class="hlqoyz1hh"/><path class="jkuojibnm"/><path class="l517yxbln"/><path class="n8qem9biv"/><path class="h-2uoubai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:compost-duotone-bold" /></template>
<style>
.h-2uoubai {
  d: path("M12 12c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

.h93exbbfx {
  fill: currentColor;
  d: path("M12 12c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hlqoyz1hh {
  d: path("M3 20a9 9 0 0 1 18 0");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.l517yxbln {
  d: path("M12 9v6");
}

.n799wlg5y {
  fill: currentColor;
  d: path("M6 12c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n8qem9biv {
  d: path("M6 12c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
