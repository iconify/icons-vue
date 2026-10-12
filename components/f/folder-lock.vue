<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sqj9bb5hd"/><rect class="ayfqfi6fr"/><path class="lpkyjcbgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-lock" /></template>
<style>
.ayfqfi6fr {
  width: 6.5px;
  height: 5px;
  x: 14.25px;
  y: 16.25px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lpkyjcbgj {
  d: path("M15.75 16.25V15a1.75 1.75 0 0 1 3.5 0v1.25");
}

.sqj9bb5hd {
  d: path("M11.75 19.25h-6.5a2.5 2.5 0 0 1-2.5-2.5v-9.5a2.5 2.5 0 0 1 2.5-2.5h3.6a2 2 0 0 1 1.6.8L11.55 7a2 2 0 0 0 1.6.8h5.6a2.5 2.5 0 0 1 2.5 2.5v2.25m-18.5-1.8h12");
}

</style>
