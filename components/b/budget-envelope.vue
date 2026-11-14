<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziesx-b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:budget-envelope" /></template>
<style>
.ziesx-b4j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 7.75h10.5V4.5q0-.25-.25-.25H7q-.25 0-.25.25zm12 .06q1.034.172 1.865.836L12 13.633L3.385 8.646q.831-.664 1.865-.836V4.5q0-1.75 1.75-1.75h10q1.75 0 1.75 1.75zm-6.374 7.339l9.263-5.363q.611.981.611 2.214v5q0 1.76-1.245 3.005T18 21.25H6q-1.76 0-3.005-1.245T1.75 17v-5q0-1.233.611-2.214l9.263 5.363q.086.05.181.075q.096.026.195.026t.195-.026t.181-.075");
}

</style>
