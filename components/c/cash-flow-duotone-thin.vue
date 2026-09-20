<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b7uyqxwtl"/><path class="yyyme3b8l"/><path class="oje-b6bwm"/><path class="mr3ctzbkt"/><path class="w8wku2xli"/><path class="ky4omnbla"/><path class="jlpxneb5g"/><path class="caiwqabfd"/><path class="pqrd0wbvk"/><path class="qnpnbmb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cash-flow-duotone-thin" /></template>
<style>
.b7uyqxwtl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.caiwqabfd {
  d: path("M6.5 10.5 9 8l2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jlpxneb5g {
  d: path("M9 8v8");
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.mr3ctzbkt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oje-b6bwm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6.5 10.5 9 8l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pqrd0wbvk {
  d: path("M15 8v8");
}

.qnpnbmb3w {
  d: path("M12.5 13.5 15 16l2.5 -2.5");
}

.w8wku2xli {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.5 13.5 15 16l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yyyme3b8l {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
