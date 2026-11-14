<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8hnf2n6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-eyewear" /></template>
<style>
.q8hnf2n6q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 14V9q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141Q3.5 8.926 3.5 9v1.645Q4.763 9.5 6.5 9.5q1.864 0 3.182 1.318q.719.719 1.046 1.6q.552-.293 1.272-.293t1.272.293q.327-.881 1.046-1.6Q15.636 9.5 17.5 9.5q1.737 0 3 1.145V9q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141T22 9v5q0 1.864-1.318 3.182T17.5 18.5t-3.182-1.318q-1.247-1.247-1.314-2.983q-.353-.574-1.004-.574t-1.004.574q-.067 1.736-1.314 2.983Q8.364 18.5 6.5 18.5t-3.182-1.318T2 14");
}

</style>
