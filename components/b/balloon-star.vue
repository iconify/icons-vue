<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7ulyo_ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:balloon-star" /></template>
<style>
.m7ulyo_ln {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.702 4.753v-.001Q13.18 3.694 12 3.694t-1.702 1.058l-.621 1.259q-.232.472-.753.548l-1.389.202q-1.166.169-1.531 1.29q-.364 1.122.479 1.945l1.006.98q.376.367.288.885l-.238 1.383q-.201 1.164.754 1.858t1.999.144l1.043-.549q.112.874.373 1.969q.633 2.661.071 4.628q-.02.071-.026.145q-.007.073.002.147q.008.073.031.143q.023.071.058.135t.084.121t.106.102t.123.08t.137.054q.143.041.292.024q.148-.017.278-.089q.131-.073.223-.19q.093-.117.134-.26q.67-2.344-.054-5.387q-.199-.837-.303-1.517l.843.444q1.045.55 2-.144t.754-1.857l-.238-1.384q-.088-.518.289-.885l1.005-.98q.843-.823.479-1.945q-.365-1.121-1.531-1.29l-1.389-.202q-.521-.076-.753-.548z");
}

</style>
