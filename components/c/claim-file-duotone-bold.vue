<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="li5ua4t9f"/><path class="v79iaqbup"/><path class="w6lrk777f"/><path class="mrtipt_up"/><path class="cux6aab4m"/><path class="t9gnp4b0n"/><path class="ae-e09b3w"/><path class="ohhz_s35v"/><path class="yb0sj-xar"/><path class="fobf5jwcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:claim-file-duotone-bold" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.cux6aab4m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9.5 10 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fobf5jwcl {
  d: path("m9.5 10 5 -5");
}

.li5ua4t9f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mrtipt_up {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 18a2 2 0 0 1 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ohhz_s35v {
  d: path("M12 12v6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t9gnp4b0n {
  d: path("M3 12a9 9 0 0 1 18 0");
}

.v79iaqbup {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w6lrk777f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yb0sj-xar {
  d: path("M12 18a2 2 0 0 1 -4 0");
}

</style>
