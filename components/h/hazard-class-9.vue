<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rra9sg-uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hazard-class-9" /></template>
<style>
.rra9sg-uk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.386 3.826l5.788 5.788q2.386 2.386 0 4.772l-5.788 5.788q-2.386 2.386-4.772 0l-5.788-5.788Q1.44 12 3.826 9.614l5.788-5.788q2.386-2.386 4.772 0M14.5 8h-5q-.114 0-.222.034q-.109.033-.203.098q-.093.064-.164.153q-.07.09-.111.196q-1.354 3.519 0 7.038q.041.106.111.196q.071.089.164.153q.094.065.203.098q.108.034.222.034h5q.114 0 .222-.034q.109-.033.203-.098q.093-.064.164-.153q.07-.09.111-.196q1.354-3.519 0-7.038q-.041-.106-.111-.196q-.071-.089-.164-.153q-.094-.065-.203-.098Q14.614 8 14.5 8");
}

</style>
