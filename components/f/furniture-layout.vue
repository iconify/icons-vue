<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f83rkybsl"/><path class="wtxb_za5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:furniture-layout" /></template>
<style>
.f83rkybsl {
  d: path("M14.1 14H5.5V5h13v5.6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wtxb_za5u {
  d: path("M10.585 18.5H2.5V11q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126q.041-.062.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036t.146-.022T4 9.5t.147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076t.119.087t.109.099t.099.109q.046.057.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T5.5 11v3h8.557m4.489-3.37q.031-.12.081-.234t.118-.218t.152-.195t.182-.167q.098-.077.208-.136t.226-.099q.118-.04.24-.061q.123-.02.247-.02q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T21.5 11v2.515M4.5 18.5v2M18 14v8m-4-4h8m-5.25-2.75L18 14l1.25 1.25m-2.5 5.5L18 22l1.25-1.25m-4-4L14 18l1.25 1.25m5.5-2.5L22 18l-1.25 1.25");
}

</style>
