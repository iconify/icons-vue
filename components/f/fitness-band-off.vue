<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7bec9bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fitness-band-off" /></template>
<style>
.e7bec9bfe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.495 5.588Q9.74 5.5 10 5.5h4q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109q.046.057.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T15.5 7v4.579m-1.04 6.849q-.224.072-.46.072h-4q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076q-.062-.041-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T8.5 17v-4.536M10 5.5v-3h4v3m-4 13v3h4v-3M3.5 3.5l17 17");
}

</style>
