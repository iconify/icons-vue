<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tyssr8bah"/><path class="z1ub6hbbw"/><path class="cji37bcwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:field-work" /></template>
<style>
.cji37bcwk {
  d: path("M9.525 14.475za.927.927 0 0 1-.362 1.535l-.168.056a.839.839 0 0 1-1.061-1.061l.056-.168a.927.927 0 0 1 1.535-.362");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tyssr8bah {
  d: path("M11.917 5.951C9.423 4.495 5.967 4.258 3 5v14a13.9 13.9 0 0 1 4.27-.379m1.83.259c1.045.23 2.033.6 2.9 1.12c2.5-1.5 6-1.75 9-1V5a14 14 0 0 0-1.817-.325M12 17.5V20");
}

.z1ub6hbbw {
  d: path("M17.303 6.697za1.5 1.5 0 0 1 0 2.121l-5.657 5.657a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121l5.657-5.657a1.5 1.5 0 0 1 2.121 0");
}

</style>
