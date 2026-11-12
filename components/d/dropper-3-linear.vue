<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bh5981mts"/><path class="w9wkd2b5z"/><path class="iudduob5r"/><path class="msronwbal"/><path class="o95ej6b5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dropper-3-linear" /></template>
<style>
.bh5981mts {
  d: path("M22 10V16.5069C22 17.1639 21.723 17.7906 21.2371 18.2329C18.2685 20.935 13.7315 20.935 10.7629 18.2329C10.277 17.7906 10 17.1639 10 16.5069V10C10 8.11438 10 7.17157 10.5858 6.58579C11.1716 6 12.1144 6 14 6H18C19.8856 6 20.8284 6 21.4142 6.58579C22 7.17157 22 8.11438 22 10Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iudduob5r {
  d: path("M18 11.4167C18 12.5672 17.1046 13.5 16 13.5C14.8954 13.5 14 12.5672 14 11.4167C14 10.6967 14.783 9.73589 15.3691 9.11743C15.7161 8.7513 16.2839 8.7513 16.6309 9.11743C17.217 9.73589 18 10.6967 18 11.4167Z");
}

.msronwbal {
  d: path("M16 21V22");
}

.o95ej6b5s {
  d: path("M2 22V8C2 5.17157 2 3.75736 2.87868 2.87868C3.75736 2 5.17157 2 8 2H11.8913L11.9355 2.00008C12.6224 2.00503 13.2869 2.24559 13.8178 2.68156L13.8517 2.70975C13.8926 2.74382 13.913 2.76086 13.9309 2.77532C14.5341 3.26249 15.2747 3.48035 16 3.43581M18.5 2L17.9774 2.52261C17.9398 2.56024 17.9209 2.57906 17.9044 2.59508C17.3724 3.11098 16.6932 3.39324 16 3.43581M16 2V3.43581M16 3.43581V6");
}

.w9wkd2b5z {
  d: path("M18 16H14");
}

</style>
