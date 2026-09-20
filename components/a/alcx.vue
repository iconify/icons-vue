<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kwuuvwbzr"/><path fill="url(#SVG97F7wYvD)" class="ocos3pbek"/><path clip-rule="evenodd" class="efg7zmbla"/><path class="h5akmabwt"/><defs><linearGradient id="SVG97F7wYvD" x1="6.349" x2="24.905" y1="6.121" y2="27.435" gradientUnits="userSpaceOnUse"><stop class="iec-__bqf"/><stop offset="1" class="p1we3jffn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:alcx" /></template>
<style>
.efg7zmbla {
  fill: var(--svg-color--ecbe9d, #ecbe9d);
  fill-rule: evenodd;
  d: path("M12 17.786a5.784 5.784 0 0 0 4.092-9.876A5.785 5.785 0 1 0 12 17.786m0-.321a5.464 5.464 0 1 0 0-10.929a5.464 5.464 0 0 0 0 10.929");
}

.ft5dv1b6b {
  fill: none;
}

.h5akmabwt {
  fill: var(--svg-color--ecbe9d, #ecbe9d);
  d: path("M11.862 7.573V6.48h.321v1.093l3.674 2.925v2.916l-.62.514l.736 1.286h-2.372l-1.575 1.298l-1.626-1.298H8.143l.675-1.257l-.675-.543v-2.919l3.719-2.925zm.16.28l-3.461 2.726l1.433 1.15l2.032-3.432l1.983 3.48l1.434-1.198zm3.514 3.066l-1.363 1.141l.903 1.588l.46-.385zm-5.29 1.013l1.937 1.559v1.401h3.237l-3.4-5.956zm1.937 3.282v.752l.913-.752zm-.321.758v-2.327l-3.398-2.732v2.35zM9.075 14.16l-.395.733H10z");
}

.iec-__bqf {
  stop-color: var(--svg-color--1a1e21, #1a1e21);
}

.kwuuvwbzr {
  fill: var(--svg-color--fff, #fff);
  d: path("M21 3H3v18h18z");
}

.ocos3pbek {
  d: path("M3 3h18v18H3z");
}

.p1we3jffn {
  stop-color: var(--svg-color--06060a, #06060a);
}

</style>
