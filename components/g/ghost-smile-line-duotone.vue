<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="wtzf3ijxf"/><path class="yy_nj5bei"/><path class="sygjb24yx"/><ellipse class="u7snxmbok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ghost-smile-line-duotone" /></template>
<style>
.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

.sygjb24yx {
  d: path("M15.5 9.5C15.5 10.0523 15.2761 10.5 15 10.5C14.7239 10.5 14.5 10.0523 14.5 9.5C14.5 8.94772 14.7239 8.5 15 8.5C15.2761 8.5 15.5 8.94772 15.5 9.5Z");
}

.u7snxmbok {
  cx: 9px;
  cy: 9.5px;
  rx: 0.5px;
  ry: 1px;
}

.wtzf3ijxf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 15C9.85038 15.6303 10.8846 16 12 16C13.1154 16 14.1496 15.6303 15 15");
}

.yy_nj5bei {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M22 12.3006V19.723C22 21.0453 20.649 21.9054 19.5008 21.314C18.5727 20.836 17.4672 20.9069 16.6039 21.4998C15.6326 22.1667 14.3674 22.1667 13.3961 21.4998L13.0435 21.2576C12.4116 20.8237 11.5884 20.8237 10.9565 21.2576L10.6039 21.4998C9.63264 22.1667 8.36736 22.1667 7.39614 21.4998C6.5328 20.9069 5.42726 20.836 4.4992 21.314C3.35098 21.9054 2 21.0453 2 19.723V12.3006C2 6.61173 6.47715 2 12 2C17.5228 2 22 6.61173 22 12.3006Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
