<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqdo_dbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lab-waste" /></template>
<style>
.gqdo_dbra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5.5h15M9 5.5v-3h4v3m-7.5 0L6.75 20q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036t.146.022t.147.007h5.5q.074 0 .147-.007t.146-.022t.142-.036q.071-.021.139-.049t.133-.063t.126-.076q.062-.041.119-.087q.057-.047.109-.099t.099-.109q.046-.057.087-.119t.076-.126q.035-.065.063-.133t.049-.139q.022-.07.036-.142q.015-.073.022-.146T15.25 20l.086-1m.516-5.978L16.5 5.5m1.5 9.25v3.5M18 21h.01");
}

</style>
