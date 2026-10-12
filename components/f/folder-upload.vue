<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sqj9bb5hd"/><path class="zh956wb4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-upload" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sqj9bb5hd {
  d: path("M11.75 19.25h-6.5a2.5 2.5 0 0 1-2.5-2.5v-9.5a2.5 2.5 0 0 1 2.5-2.5h3.6a2 2 0 0 1 1.6.8L11.55 7a2 2 0 0 0 1.6.8h5.6a2.5 2.5 0 0 1 2.5 2.5v2.25m-18.5-1.8h12");
}

.zh956wb4f {
  d: path("M17.5 20.25v-6.5m-2.5 2.5l2.5-2.5l2.5 2.5");
}

</style>
