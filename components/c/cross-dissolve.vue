<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr29evbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cross-dissolve" /></template>
<style>
.zr29evbeq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 3.25h5.5q1.76 0 3.005 1.245T15.75 7.5v1.75H18q1.76 0 3.005 1.245T22.25 13.5v3q0 1.76-1.245 3.005T18 20.75h-5.5q-1.76 0-3.005-1.245T8.25 16.5v-1.75H6q-1.76 0-3.005-1.245T1.75 10.5v-3q0-1.76 1.245-3.005T6 3.25m4.5 6q-2.25 0-2.25 2.25v1q0 .932.659 1.591t1.591.659h3q.932 0 1.591-.659t.659-1.591v-1q0-2.25-2.25-2.25z");
}

</style>
