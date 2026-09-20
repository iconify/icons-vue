<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dp8rry9sk"/><path class="lf1zqhjea"/><path class="yt70p9btb"/><path class="kr5tlbbsn"/><path class="f34u2hrkg"/><path class="srzgk7jml"/><path class="ic_pehd5a"/><path class="fbw2ldgtv"/><path class="xsyfe-byx"/><path class="mvo4nxq3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:car-dashboard-duotone-bold" /></template>
<style>
.dp8rry9sk {
  fill: currentColor;
  d: path("M6 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.f34u2hrkg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 10v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fbw2ldgtv {
  d: path("M12 10v7");
}

.ic_pehd5a {
  d: path("M3 17h18");
}

.kr5tlbbsn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lf1zqhjea {
  fill: currentColor;
  d: path("M16 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mvo4nxq3c {
  d: path("M16 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.xsyfe-byx {
  d: path("M6 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.yt70p9btb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
