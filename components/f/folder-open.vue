<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e0vce8bpo"/><path class="eek_nfxmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-open" /></template>
<style>
.e0vce8bpo {
  d: path("M2.75 12V7.25a2.5 2.5 0 0 1 2.5-2.5h3.6a2 2 0 0 1 1.6.8L11.55 7a2 2 0 0 0 1.6.8h3.6a2.5 2.5 0 0 1 2.5 2.5v.5");
}

.eek_nfxmu {
  d: path("M7.5 10.75H20q1.25 0 .83 1.18l-2.16 6.14q-.42 1.18-1.67 1.18H4q-1.25 0-.77-1.16l2.54-6.18q.48-1.16 1.73-1.16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
