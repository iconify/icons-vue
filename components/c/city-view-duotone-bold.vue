<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jfxpixb_o"/><path class="opamo1bit"/><path class="yudlmhraw"/><path class="c3ss2dnim"/><path class="tp3wfdbxm"/><path class="hb_6svr8j"/><path class="bi34yzw-v"/><path class="urzumpb2c"/><path class="qowfo405a"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:city-view-duotone-bold" /></template>
<style>
.bi34yzw-v {
  d: path("M12 21V4h7v17");
}

.c3ss2dnim {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hb_6svr8j {
  d: path("M3 21V10h7v11");
}

.jfxpixb_o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 21V10h7v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.opamo1bit {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 21V4h7v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.qowfo405a {
  d: path("M12 9h7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tp3wfdbxm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.urzumpb2c {
  d: path("M3 14h7");
}

.yudlmhraw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 14h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
