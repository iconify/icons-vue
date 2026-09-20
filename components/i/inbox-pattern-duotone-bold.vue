<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x9vxhbcxr"/><path class="d-zgcbbzy"/><path class="qhw9x6kcs"/><path class="f-52c6b3g"/><path class="rr985ibot"/><path class="rqm7ypbhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:inbox-pattern-duotone-bold" /></template>
<style>
.d-zgcbbzy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f-52c6b3g {
  d: path("M4 10v10h16V10");
}

.qhw9x6kcs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 5.5 12 8l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rqm7ypbhc {
  d: path("M9.5 5.5 12 8l2.5 -2.5");
}

.rr985ibot {
  d: path("M12 3v2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x9vxhbcxr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 10v10h16V10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
