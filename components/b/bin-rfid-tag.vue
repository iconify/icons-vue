<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkmv5vvcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bin-rfid-tag" /></template>
<style>
.nkmv5vvcq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6h13M4 6l1.25 13.5q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022T6.75 21h1.421m4.651-7.673L13.5 6M7 3h4m5.5 17.75h.01m-3.01 0a3 3 0 0 1 3-3m-5.5 3a5.5 5.5 0 0 1 5.5-5.5");
}

</style>
