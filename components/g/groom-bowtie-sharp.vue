<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="q5vsb_bxb"/><path class="o8s5a5btn"/><path class="a2ofppv1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:groom-bowtie-sharp" /></template>
<style>
.a2ofppv1f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 16h.01M12 19h.01");
}

.o8s5a5btn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3L12 4.25L14.5 3v4L12 6L9.5 7Z");
}

.q5vsb_bxb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25V7l.45-.89l.85-1.72l.45-.89l.6.8l6.3 8.4l.6.8l.6-.8l6.3-8.4l.6-.8l.45.89l.85 1.72l.45.89v14.25H2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
