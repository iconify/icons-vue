<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qov5as_5m"/><path class="uih_zvhtv"/><path class="xogm81bqq"/><path class="pfpu_3ppl"/><path class="zjf1fhb5j"/><path class="adb8tobrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bunsen-burner-duotone-bold" /></template>
<style>
.adb8tobrr {
  d: path("M12 3c1 2.5 3 3.5 3 5a3 3 0 1 1 -6 0c0 -2 1.5 -2.5 1.5 -3.5 0.5 1 1.5 1 1.5 -1.5");
}

.pfpu_3ppl {
  d: path("M12 8v4");
}

.qov5as_5m {
  fill: currentColor;
  d: path("M12 3c1 2.5 3 3.5 3 5a3 3 0 1 1 -6 0c0 -2 1.5 -2.5 1.5 -3.5 0.5 1 1.5 1 1.5 -1.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uih_zvhtv {
  d: path("M4 21h16");
}

.xogm81bqq {
  d: path("M10 21v-9h4v9");
}

.zjf1fhb5j {
  d: path("M14 17h5");
}

</style>
