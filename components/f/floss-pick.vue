<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jvhq8tbwj"/><path class="yq5tygk5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:floss-pick" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jvhq8tbwj {
  d: path("M10.232 13.768za2 2 0 0 1 0 2.828L7.05 19.778a2 2 0 0 1-2.828 0a2 2 0 0 1 0-2.828l3.182-3.182a2 2 0 0 1 2.828 0");
}

.yq5tygk5i {
  d: path("M14.828 3.515L11.293 7.05l-1.061 6.718l6.718-1.061l3.535-3.535m-5.657-5.657l5.657 5.657");
}

</style>
