<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l1bh8u9gc"/><path class="h0ja_-bvy"/><path class="r-xdlybih"/><path class="xh8znm0ox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:honeycomb-grid" /></template>
<style>
.h0ja_-bvy {
  d: path("m10.171 8.335l.5.25a1.5 1.5 0 0 1 .829 1.342v.646a1.5 1.5 0 0 1-.829 1.342l-.5.25a1.5 1.5 0 0 1-1.342 0l-.5-.25a1.5 1.5 0 0 1-.829-1.342v-.646a1.5 1.5 0 0 1 .829-1.342l.5-.25a1.5 1.5 0 0 1 1.342 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l1bh8u9gc {
  d: path("M2.5 12a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

.r-xdlybih {
  d: path("m8.171 11.835l.5.25a1.5 1.5 0 0 1 .829 1.342v.646a1.5 1.5 0 0 1-.829 1.342l-.5.25a1.5 1.5 0 0 1-1.342 0l-.5-.25a1.5 1.5 0 0 1-.829-1.342v-.646a1.5 1.5 0 0 1 .829-1.342l.5-.25a1.5 1.5 0 0 1 1.342 0");
}

.xh8znm0ox {
  d: path("m12.171 11.835l.5.25a1.5 1.5 0 0 1 .829 1.342v.646a1.5 1.5 0 0 1-.829 1.342l-.5.25a1.5 1.5 0 0 1-1.342 0l-.5-.25a1.5 1.5 0 0 1-.829-1.342v-.646a1.5 1.5 0 0 1 .829-1.342l.5-.25a1.5 1.5 0 0 1 1.342 0M18.25 7.5l3.25-2m-3.25 11l3.25 2");
}

</style>
