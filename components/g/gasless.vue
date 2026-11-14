<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ykdszvb6m"/><path class="yqq2r1y6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gasless" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ykdszvb6m {
  d: path("M7.4 3.5H14v6.6m0 7.8v2.6H4V7.9M2.5 20.5h13M14 8h1.5q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076t.119.087t.109.099t.099.109q.046.057.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T17 9.5V13q0 .04.002.079m1.455 1.42l.043.001q.074 0 .147-.007t.146-.022q.072-.014.142-.036q.071-.021.139-.049t.133-.063t.126-.076q.062-.041.119-.087q.057-.047.109-.099t.099-.109t.087-.119t.076-.126t.063-.133t.049-.139t.036-.142q.015-.073.022-.146T20 13V7l-2.5-2.5");
}

.yqq2r1y6k {
  d: path("M10.65 6.75h.6v.6M3.5 3.5l17 17");
}

</style>
