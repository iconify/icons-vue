<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sk-dcrbqg"/><path class="iloxv9qhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:badge-ribbon" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iloxv9qhl {
  d: path("M8.75 14.5v7L12 19.25l3.25 2.25v-7");
}

.sk-dcrbqg {
  d: path("m12.744 2.848l.229.184a1.5 1.5 0 0 0 1.169.313l.29-.045a1.19 1.19 0 0 1 1.288.744l.107.274a1.5 1.5 0 0 0 .855.855l.274.107a1.19 1.19 0 0 1 .744 1.288l-.045.29a1.5 1.5 0 0 0 .313 1.169l.184.229a1.19 1.19 0 0 1 0 1.488l-.184.229a1.5 1.5 0 0 0-.313 1.169l.045.29a1.19 1.19 0 0 1-.744 1.288l-.274.107a1.5 1.5 0 0 0-.855.855l-.107.274a1.19 1.19 0 0 1-1.288.744l-.29-.045a1.5 1.5 0 0 0-1.169.313l-.229.184a1.19 1.19 0 0 1-1.488 0l-.229-.184a1.5 1.5 0 0 0-1.169-.313l-.29.045a1.19 1.19 0 0 1-1.288-.744l-.107-.274a1.5 1.5 0 0 0-.855-.855l-.274-.107a1.19 1.19 0 0 1-.744-1.288l.045-.29a1.5 1.5 0 0 0-.313-1.169l-.184-.229a1.19 1.19 0 0 1 0-1.488l.184-.229a1.5 1.5 0 0 0 .313-1.169l-.045-.29a1.19 1.19 0 0 1 .744-1.288l.274-.107a1.5 1.5 0 0 0 .855-.855l.107-.274A1.19 1.19 0 0 1 9.568 3.3l.29.045a1.5 1.5 0 0 0 1.169-.313l.229-.184a1.19 1.19 0 0 1 1.488 0");
}

</style>
