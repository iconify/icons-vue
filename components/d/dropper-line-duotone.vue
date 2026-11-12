<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ik-3qexjt"/><path class="uhfh519di"/><path class="bqpt78r5r"/><path class="j_6w1fbre"/><path class="xjwylvpfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dropper-line-duotone" /></template>
<style>
.bqpt78r5r {
  d: path("M16 21V22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ik-3qexjt {
  d: path("M22 10H18");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j_6w1fbre {
  d: path("M2 22V8C2 5.17157 2 3.75736 2.87868 2.87868C3.75736 2 5.17157 2 8 2H11.8913L11.9355 2.00008C12.6224 2.00503 13.2869 2.24559 13.8178 2.68156L13.8517 2.70975C13.8926 2.74382 13.913 2.76086 13.9309 2.77532C14.5341 3.26249 15.2747 3.48035 16 3.43581M16 3.43581C16.6932 3.39324 17.3724 3.11098 17.9044 2.59508C17.9209 2.57906 17.9398 2.56024 17.9774 2.52261L18.5 2M16 3.43581V2M16 3.43581V6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.uhfh519di {
  d: path("M22 13H19");
}

.xjwylvpfw {
  d: path("M22 16.5069V10C22 8.11438 22 7.17157 21.4142 6.58579C20.8284 6 19.8856 6 18 6H14C12.1144 6 11.1716 6 10.5858 6.58579C10 7.17157 10 8.11438 10 10V16.5069C10 17.1639 10.277 17.7906 10.7629 18.2329C13.7315 20.935 18.2685 20.935 21.2371 18.2329C21.723 17.7906 22 17.1639 22 16.5069Z");
}

</style>
