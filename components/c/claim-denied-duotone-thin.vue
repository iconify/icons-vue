<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rcjv44b9n"/><path class="fx63l30wc"/><path class="j15uiubkt"/><path class="w-bszmb4l"/><path class="tlelbwb4f"/><path class="vfb3fry3t"/><path class="t9gnp4b0n"/><path class="ae-e09b3w"/><path class="ohhz_s35v"/><path class="yb0sj-xar"/><path class="z-r90accw"/><path class="km7jpmbti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:claim-denied-duotone-thin" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.fx63l30wc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j15uiubkt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.km7jpmbti {
  d: path("m14.5 5 -5 5");
}

.ohhz_s35v {
  d: path("M12 12v6");
}

.rcjv44b9n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t9gnp4b0n {
  d: path("M3 12a9 9 0 0 1 18 0");
}

.tlelbwb4f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9.5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vfb3fry3t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14.5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w-bszmb4l {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 18a2 2 0 0 1 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yb0sj-xar {
  d: path("M12 18a2 2 0 0 1 -4 0");
}

.z-r90accw {
  d: path("m9.5 5 5 5");
}

</style>
