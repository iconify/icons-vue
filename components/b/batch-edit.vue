<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ru-xm8bcu"/><path class="kfkqm5b9d"/><path class="dsv3_bb4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:batch-edit" /></template>
<style>
.dsv3_bb4y {
  d: path("M8.5 2h10A1.5 1.5 0 0 1 20 3.5v7m-14.5 3L8 11l1.75 1.75L11 11.5m3.75 9.75l.75-2.75l3.75-3.75l2 2l-3.75 3.75Zm.75-2.75l2 2");
}

.kfkqm5b9d {
  d: path("M5.5 4.75h10q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076t.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T17 6.25v6.779");
}

.ru-xm8bcu {
  d: path("M13.6 16.5H2.5v-9H14v8.6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
