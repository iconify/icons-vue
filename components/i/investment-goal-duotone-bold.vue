<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o5r75dbio"/><path class="gpjnysbcs"/><path class="e7x4tm5bp"/><path class="wsird7b6w"/><path class="lob-p4n4f"/><path class="rk3avflyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:investment-goal-duotone-bold" /></template>
<style>
.e7x4tm5bp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 6h4v3.5h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gpjnysbcs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 5v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lob-p4n4f {
  d: path("M18 5v8");
}

.o5r75dbio {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m2 21 5 -5 4 4 7 -7 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rk3avflyg {
  d: path("M18 6h4v3.5h-4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wsird7b6w {
  d: path("m2 21 5 -5 4 4 7 -7 4 4");
}

</style>
