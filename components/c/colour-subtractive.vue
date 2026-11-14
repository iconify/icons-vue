<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg6oa36qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:colour-subtractive" /></template>
<style>
.dg6oa36qu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.081 4.581Q2.25 6.411 2.25 9t1.831 4.419q.771.772 1.678 1.219q-.009.179-.009.362q0 2.589 1.831 4.419Q9.411 21.25 12 21.25t4.419-1.831T18.25 15q0-.183-.009-.362q.907-.447 1.678-1.219Q21.75 11.589 21.75 9t-1.831-4.419Q18.089 2.75 15.5 2.75q-1.969 0-3.5 1.059Q10.469 2.75 8.5 2.75q-2.589 0-4.419 1.831m5.646 4.47q2.273-.887 4.546 0q.058.023.113.056q.054.032.102.073t.088.09t.072.103t.054.113t.034.121t.014.125t-.008.126q-.353 2.436-2.272 3.977q-.05.04-.106.071t-.115.052t-.123.031Q12.064 14 12 14t-.126-.011q-.063-.01-.123-.031q-.06-.022-.115-.052q-.056-.031-.106-.071q-1.919-1.541-2.272-3.977q-.009-.063-.008-.126q.002-.063.014-.125t.034-.121t.054-.113t.072-.103t.088-.09t.102-.073t.113-.056");
}

</style>
