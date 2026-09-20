<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="lujrvhf4j"/><path class="ald7lxbvs"/><path class="sh-bzloxt"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="d4s5t4bpo"/><path class="y4-ssjnrw"/><path class="j4if4rbfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-bar-duotone-thin" /></template>
<style>
.ald7lxbvs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d4s5t4bpo {
  d: path("M8 12v8");
}

.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j4if4rbfv {
  d: path("M18 14v6");
}

.lujrvhf4j {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.sh-bzloxt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y4-ssjnrw {
  d: path("M13 8v12");
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
