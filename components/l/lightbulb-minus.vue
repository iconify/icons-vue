<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sw40wqn0o"/><path class="imatpjbxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lightbulb-minus" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.imatpjbxd {
  d: path("m7.75 11.5l2 2l2-2m-2 2V15M15 18h6");
}

.sw40wqn0o {
  d: path("M7.25 15a6.5 6.5 0 1 1 5 0v2.5h-5ZM8 20.5h3.5");
}

</style>
