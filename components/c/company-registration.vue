<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o2qrbxbwg"/><path class="kyupk_-5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:company-registration" /></template>
<style>
.kyupk_-5l {
  d: path("M7 21.5v-4h3v4m4.75-3.5l2 2L21 15.75");
}

.o2qrbxbwg {
  d: path("M14.264 21.5H3.5V4q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036q.073-.015.146-.022T5 2.5h7q.074 0 .147.007t.146.022t.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109q.046.057.087.119t.076.126t.063.133t.049.139t.036.142t.022.146T13.5 4v5.5h5q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T20 11v1.836m0 7.9v.764h-.836M7 7.5h3M7 12h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
