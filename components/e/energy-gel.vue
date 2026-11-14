<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c7pvsf85o"/><path class="eb7e8szoo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:energy-gel" /></template>
<style>
.c7pvsf85o {
  d: path("m5.5 3.5l2.25-1l2 1l2.25-1l2.25 1l2-1l2.25 1V20a1.5 1.5 0 0 1-1.5 1.5H7A1.5 1.5 0 0 1 5.5 20Zm0 3h13");
}

.eb7e8szoo {
  d: path("m11.924 10.716l-2.25 2.486a.777.777 0 0 0 .576 1.298a1.31 1.31 0 0 1 1.256 1.679l-.131.446a.454.454 0 0 0 .786.417l2.224-2.693A.824.824 0 0 0 13.75 13a1.26 1.26 0 0 1-1.197-1.66l.072-.215a.415.415 0 0 0-.701-.409");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
