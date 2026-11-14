<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brwho6-6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-personal-care" /></template>
<style>
.brwho6-6d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 2.5q3 0 3 3t-3 3t-3-3t3-3M3.495 3.995Q2.25 5.24 2.25 7t1.245 3.005T6.5 11.25t3.005-1.245T10.75 7T9.505 3.995T6.5 2.75T3.495 3.995M20 7.5q-2.25 0-2.25 2.25T20 12t2.25-2.25T20 7.5m-2.25 5.75q1.864 0 3.182 1.318t1.318 3.182t-1.318 3.182t-3.182 1.318H6.25q-1.864 0-3.182-1.318T1.75 17.75t1.318-3.182T6.25 13.25zm-12.5 4.5Q5.25 16 7 16h10q1.75 0 1.75 1.75T17 19.5H7q-1.75 0-1.75-1.75");
}

</style>
