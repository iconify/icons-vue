<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pwgr6xbiq"/><path class="ak1x5b97m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:code-editor" /></template>
<style>
.ak1x5b97m {
  d: path("M14.5 2.5V6a2 2 0 0 0 2 2H20M7.5 6h4m-4 4H14m-4.25 3.5L7.25 16l2.5 2.5m4.5-5l2.5 2.5l-2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pwgr6xbiq {
  d: path("M6 2.5h8.5L20 8v11.5a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2");
}

</style>
