<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="tdo704kha"/><path class="nqrxs2bux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:globe-europe-africa" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nqrxs2bux {
  d: path("m11 9.5l1.5-2H16l.75 2.5l1.25.5l-.75 1.75l-1.75 4.25l-.75 1.25l-1-2.25l-.25-2.5l-1.5-1l-1-1.5Z");
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

.tdo704kha {
  d: path("M12 2.5C6.5 6 6.5 18 12 21.5");
}

</style>
