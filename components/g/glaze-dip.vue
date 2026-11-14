<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czj79yczj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:glaze-dip" /></template>
<style>
.czj79yczj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 1.75h-3q-2.75 0-2.75 2.75t2.75 2.75h3q2.75 0 2.75-2.75T13.5 1.75m-.89 6.314l1.25 1.75l.015.021q1.088 1.641-.393 2.937q-1.482 1.297-2.964 0t-.393-2.937l.015-.021l1.25-1.75q.043-.06.096-.111q.054-.05.117-.089t.132-.066t.142-.038t.146-.01q.074.003.146.019q.072.017.139.047q.068.031.128.074q.102.072.174.174M3 14.25h18q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q-.001 3.075-2.948 5.203q-2.833 2.045-6.802 2.045t-6.802-2.045Q2.251 18.075 2.25 15q0-.074.014-.146t.043-.141q.028-.068.069-.129q.041-.062.093-.114q.053-.052.114-.093t.13-.07t.14-.043q.073-.014.147-.014");
}

</style>
