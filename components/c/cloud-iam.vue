<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2n6clbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloud-iam" /></template>
<style>
.u2n6clbzq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 19.75q-.051 0-.101-.007q-3.507-.476-3.871-3.996q-.34-3.287 2.546-4.537q.883-5.075 6.195-5.414q5.259-.336 6.802 4.485q1.603.175 2.788 1.36Q21.75 13.032 21.75 15t-1.391 3.359T17 19.75h-1.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T16 19q0-1.809-1.37-3.055q-1.315-1.195-3.13-1.195t-3.13 1.195Q7 17.191 7 19q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014zm1.75 0q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T8.5 19q0-2.75 3-2.75t3 2.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014zm3.75-11.5q-2.75 0-2.75 2.75t2.75 2.75T14.25 11T11.5 8.25");
}

</style>
