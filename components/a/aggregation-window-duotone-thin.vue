<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="bvowdpkby"/><path class="bjr-m2bij"/><path class="ke9b-u_dj"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="kswphkyfs"/><path class="rgj9t7gfi"/><path class="g45hqpb0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:aggregation-window-duotone-thin" /></template>
<style>
.bjr-m2bij {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 7H16v10h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bvowdpkby {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 7H8v10h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g45hqpb0s {
  d: path("M10.5 12h3");
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

.ke9b-u_dj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kswphkyfs {
  d: path("M10.5 7H8v10h2.5");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.rgj9t7gfi {
  d: path("M13.5 7H16v10h-2.5");
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
