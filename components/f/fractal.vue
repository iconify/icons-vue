<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9rdlg1is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fractal" /></template>
<style>
.d9rdlg1is {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.95 5.634Q13.301 4.506 12 4.506t-1.95 1.128L3.145 17.628q-.647 1.124.002 2.248q.649 1.123 1.947 1.124h13.813q1.297-.001 1.946-1.124t.002-2.248z");
}

</style>
