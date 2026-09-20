<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jqvj67jvf"/><path class="qgw5bw59f"/><path class="o2mxw0jtm"/><path class="i9lkiobzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:guitar-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i9lkiobzn {
  d: path("M10 5V2h4v3Z");
}

.jqvj67jvf {
  d: path("M12 21c-3.5 0 -6 -2 -6 -4.5 0 -3 2.5 -4 3 -5.5h6c0.5 1.5 3 2.5 3 5.5 0 2.5 -2.5 4.5 -6 4.5");
}

.o2mxw0jtm {
  d: path("M12 5v6");
}

.qgw5bw59f {
  d: path("M10 16.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
