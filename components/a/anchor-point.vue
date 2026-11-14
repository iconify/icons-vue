<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9wqcf_et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:anchor-point" /></template>
<style>
.p9wqcf_et {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.757 3.757Q6 5.515 6 8t1.757 4.243q1.486 1.486 3.493 1.715v.792h-7q-2.5 0-2.5 2.5v1q0 2.5 2.5 2.5h15.5q1.036 0 1.768-.732t.732-1.768v-1q0-1.036-.732-1.768t-1.768-.732h-7v-.792q2.007-.229 3.493-1.715Q18 10.485 18 8t-1.757-4.243Q14.485 2 12 2T7.757 3.757");
}

</style>
