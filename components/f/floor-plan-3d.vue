<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bs9oe1ajk"/><path class="rnxct9jcs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:floor-plan-3d" /></template>
<style>
.bs9oe1ajk {
  d: path("m4.508 13.232l6.691-4.226a1.5 1.5 0 0 1 1.602 0l6.691 4.226a1.5 1.5 0 0 1 0 2.536l-6.691 4.226a1.5 1.5 0 0 1-1.602 0l-6.691-4.226a1.5 1.5 0 0 1 0-2.536");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rnxct9jcs {
  d: path("M2.5 14.5V10L12 4l9.5 6v4.5M12 4v4.5m-4.75 3l4.75 3");
}

</style>
