<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pi7_qnb3o"/><path class="mzjao6bpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:guard" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mzjao6bpx {
  d: path("M9.65 7.75a3.25 3.25 0 1 0 4.7 0Zm-4.4 13.5v-.75A3.75 3.75 0 0 1 9 16.75h6a3.75 3.75 0 0 1 3.75 3.75v.75Z");
}

.pi7_qnb3o {
  d: path("m7.45 7.03l.35-1.31q.2-.72.92-.94l2.56-.81q.72-.22 1.44 0l2.56.81q.72.22.92.94l.35 1.31q.2.72-.55.72H8q-.75 0-.55-.72");
}

</style>
