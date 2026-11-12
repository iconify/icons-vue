<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="wtzf3ijxf"/><path class="b5784bc1r"/><path class="sygjb24yx"/><ellipse class="u7snxmbok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ghost-smile-broken" /></template>
<style>
.b5784bc1r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M22 12.3006C22 6.61173 17.5228 2 12 2C6.47715 2 2 6.61173 2 12.3006V19.723C2 21.0453 3.35098 21.9054 4.4992 21.314C5.42726 20.836 6.5328 20.9069 7.39614 21.4998C8.36736 22.1667 9.63264 22.1667 10.6039 21.4998L10.9565 21.2576C11.5884 20.8237 12.4116 20.8237 13.0435 21.2576L13.3961 21.4998C14.3674 22.1667 15.6326 22.1667 16.6039 21.4998C17.4672 20.9069 18.5727 20.836 19.5008 21.314C20.649 21.9054 22 21.0453 22 19.723V16.0118");
}

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

</style>
