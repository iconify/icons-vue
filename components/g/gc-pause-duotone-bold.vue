<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ipy94dbtd"/><path class="uyr1302ms"/><path class="k2jvumbfi"/><path class="tamizsb5w"/><path class="e7pgrp-wx"/><path class="wp75hkmty"/><path class="rutulxlvn"/><path class="e69i7fcek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gc-pause-duotone-bold" /></template>
<style>
.e69i7fcek {
  d: path("M17 12h5");
}

.e7pgrp-wx {
  d: path("M2 12h6");
}

.ipy94dbtd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k2jvumbfi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rutulxlvn {
  d: path("M14 7v10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tamizsb5w {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uyr1302ms {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wp75hkmty {
  d: path("M11 7v10");
}

</style>
