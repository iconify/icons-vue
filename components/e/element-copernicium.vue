<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulof0y8vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:element-copernicium" /></template>
<style>
.ulof0y8vw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 2.25h9.25q2.123 0 3.624 1.501t1.501 3.624v9.25q0 2.123-1.501 3.624t-3.624 1.501h-9.25q-2.123 0-3.624-1.501T2.25 16.625v-9.25q0-2.123 1.501-3.624T7.375 2.25M4.849 16.122v.001q.785 1.369 3.585.798q1.613-.329 3.413-1.173q.076.002.153.002q2.808 0 3.513-2.103q5.019-3.361 3.638-5.77q-.785-1.369-3.585-.798q-1.613.329-3.413 1.173q-.076-.002-.153-.002q-2.808 0-3.513 2.103q-5.018 3.36-3.638 5.769m1.302-.745q.246.428 1.983.074q.662-.135 1.367-.37q-1.112-.814-1.236-2.616q-.661.566-1.18 1.15q-1.182 1.331-.934 1.762m8.348-6.458q1.112.814 1.236 2.616q.661-.566 1.18-1.15q1.182-1.331.934-1.762q-.245-.429-1.983-.074q-.662.135-1.367.37");
}

</style>
