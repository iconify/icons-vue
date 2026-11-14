<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db99vrbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bucket" /></template>
<style>
.db99vrbrw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 8v-.002q.001-2.68 3.076-4.187Q8.373 2.563 12 2.563t6.174 1.248Q21.25 5.319 21.25 8q0 .06-.01.119v.004l-2.25 13.5q-.011.065-.033.128q-.022.062-.055.119q-.032.058-.075.109t-.092.093q-.051.043-.108.076t-.119.056t-.127.034q-.065.012-.131.012H5.75q-.066 0-.131-.012q-.065-.011-.127-.034t-.119-.056t-.108-.076t-.092-.093q-.043-.051-.075-.109q-.033-.057-.055-.119q-.022-.063-.033-.128l-2.25-13.5Q2.75 8.062 2.75 8M12 4.063q-6.973 0-7.672 3.187h15.344Q18.973 4.063 12 4.063M6.385 20.75h11.23l2-12H4.385z");
}

</style>
