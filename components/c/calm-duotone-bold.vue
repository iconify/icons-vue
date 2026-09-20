<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lv2tvb6se"/><path class="l8dn9jbyp"/><path class="olqfcgidt"/><path class="fqgwxackw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:calm-duotone-bold" /></template>
<style>
.fqgwxackw {
  d: path("M12 4c5 0 8 3 8 8 -5 0 -8 -3 -8 -8");
}

.l8dn9jbyp {
  d: path("M2 15h20");
}

.lv2tvb6se {
  fill: currentColor;
  d: path("M12 4c5 0 8 3 8 8 -5 0 -8 -3 -8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.olqfcgidt {
  d: path("M6 19h12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
