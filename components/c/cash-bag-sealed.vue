<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lrw832bdm"/><path class="fknuzw5jw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cash-bag-sealed" /></template>
<style>
.fknuzw5jw {
  d: path("M12.75 12c-.25-.75-1-1.25-2.25-1.25s-2 .75-2 1.75c0 2 4.25 1.25 4.25 3.5q-.001.27-.092.51m-.397.595c-.411.399-1.045.645-1.761.645c-1.25 0-2-.5-2.25-1.25m2.25-7v1.25m0 7V19m5.75-1.5h3.5a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 19.75 22h-3.5a1.75 1.75 0 0 1-1.75-1.75v-1a1.75 1.75 0 0 1 1.75-1.75m0 0v-1.25a1.75 1.75 0 0 1 3.5 0v1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lrw832bdm {
  d: path("M19.629 12.004C18.796 9.989 17.317 8.159 15 7H9c-4 2-5.5 6-5.5 9.5c0 3 2 5 5 5h3.345M9 7L7.5 3h9L15 7");
}

</style>
