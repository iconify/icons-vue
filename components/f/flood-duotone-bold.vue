<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q2zf-bc9g"/><path class="jxrfnhgqt"/><path class="nb-335jgt"/><path class="wlpa9-b1f"/><path class="pzm21jb5s"/><path class="fcnh_acnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flood-duotone-bold" /></template>
<style>
.fcnh_acnz {
  d: path("m3 19 2.5 -2.5L8 19l2.5 -2.5L13 19l2.5 -2.5L18 19l2.5 -2.5");
}

.jxrfnhgqt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 11v5h10v-5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nb-335jgt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 19 2.5 -2.5L8 19l2.5 -2.5L13 19l2.5 -2.5L18 19l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pzm21jb5s {
  d: path("M7 11v5h10v-5");
}

.q2zf-bc9g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 11 7 -7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wlpa9-b1f {
  d: path("m5 11 7 -7 7 7");
}

</style>
