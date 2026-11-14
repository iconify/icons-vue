<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rc0fszbhx"/><path class="zgqvh7bcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bottle-bag" /></template>
<style>
.rc0fszbhx {
  d: path("M13.895 21.447q-.194.053-.395.053h-7q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T5 20v-8.5C5 9.5 5.5 8 8 7V2.5h4V7c2.5 1 3 2.5 3 4.5v1.44");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zgqvh7bcb {
  d: path("M6.75 12.5H11V17H6.75Zm11.25 5c-1.5-2.25-3.75-2.25-3.75-.75s2.25 2 3.75.75Zm0 0c1.5-2.25 3.75-2.25 3.75-.75s-2.25 2-3.75.75Zm-.75 1.75l-.5 2.25m2-2.25l.5 2.25");
}

</style>
