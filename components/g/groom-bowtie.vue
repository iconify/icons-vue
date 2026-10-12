<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="alutsn5wm"/><path class="o8s5a5btn"/><path class="a2ofppv1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:groom-bowtie" /></template>
<style>
.a2ofppv1f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 16h.01M12 19h.01");
}

.alutsn5wm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25V8q0-1 .45-1.89l.85-1.72Q4.5 3.5 5.1 4.3l6.3 8.4q.6.8 1.2 0l6.3-8.4q.6-.8 1.05.09l.85 1.72q.45.89.45 1.89v12.25q0 1-1 1H3.75q-1 0-1-1");
}

.o8s5a5btn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3L12 4.25L14.5 3v4L12 6L9.5 7Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
