<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t4wfbu4kp"/><path class="vygzwktag"/><path class="hhwp_ccfq"/><path class="e2xrf551z"/><path class="kzhp4ccpt"/><path class="ky4omnbla"/><path class="jlpxneb5g"/><path class="caiwqabfd"/><path class="pqrd0wbvk"/><path class="qnpnbmb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cash-flow-duotone-bold" /></template>
<style>
.caiwqabfd {
  d: path("M6.5 10.5 9 8l2.5 2.5");
}

.e2xrf551z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hhwp_ccfq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6.5 10.5 9 8l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jlpxneb5g {
  d: path("M9 8v8");
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.kzhp4ccpt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.5 13.5 15 16l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pqrd0wbvk {
  d: path("M15 8v8");
}

.qnpnbmb3w {
  d: path("M12.5 13.5 15 16l2.5 -2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t4wfbu4kp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vygzwktag {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
