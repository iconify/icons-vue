<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kjydelb3x"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gift-aid" /></template>
<style>
.kjydelb3x {
  d: path("M3 7.5h18V12H3ZM4.5 12v7.5q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022T6 21h6.079M12 7.5v7.6m0-7.6c-2.5 0-4.5-1-4.5-2.5A1.5 1.5 0 0 1 9 3.5c1.5 0 3 2 3 4c0-2 1.5-4 3-4A1.5 1.5 0 0 1 16.5 5c0 1.5-2 2.5-4.5 2.5ZM14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
