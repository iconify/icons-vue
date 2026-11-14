<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="huyn6ubti"/><path class="hhiigz10t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campus-map" /></template>
<style>
.hhiigz10t {
  d: path("M12.323 10.43za1.38 1.38 0 0 0 1.07.777a.358.358 0 0 1 .2.615a1.38 1.38 0 0 0-.409 1.258a.358.358 0 0 1-.523.38a1.38 1.38 0 0 0-1.322 0a.358.358 0 0 1-.523-.38a1.38 1.38 0 0 0-.409-1.258a.358.358 0 0 1 .2-.615a1.38 1.38 0 0 0 1.07-.777a.358.358 0 0 1 .646 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.huyn6ubti {
  d: path("m4.197 5.101l4.25-1.417a1.75 1.75 0 0 1 1.106 0l4.894 1.632a1.75 1.75 0 0 0 1.106 0l3.144-1.048A1.75 1.75 0 0 1 21 5.928v11.311a1.75 1.75 0 0 1-1.197 1.66l-4.25 1.417a1.75 1.75 0 0 1-1.106 0l-4.894-1.632a1.75 1.75 0 0 0-1.106 0l-3.144 1.048A1.75 1.75 0 0 1 3 18.072V6.761a1.75 1.75 0 0 1 1.197-1.66M9 3.5v15m6-13v15");
}

</style>
