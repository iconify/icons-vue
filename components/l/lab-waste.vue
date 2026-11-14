<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu7834ryl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-waste" /></template>
<style>
.mu7834ryl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5.5h15M9 5.5v-3h4v3m-7.5 0L6.75 20q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036t.146.022t.147.007h5.5q.071 0 .141-.007q.07-.006.14-.019q.069-.014.137-.033t.133-.046t.129-.058t.123-.07t.115-.081t.108-.091q.051-.049.098-.102t.088-.11q.042-.057.078-.117t.066-.125t.054-.13q.024-.067.042-.135t.029-.138t.016-.14m.699-8.172L16.5 5.5m1.5 9.25v3.5M18 21h.01");
}

</style>
