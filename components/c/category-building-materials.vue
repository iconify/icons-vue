<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlnvcrx4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-building-materials" /></template>
<style>
.jlnvcrx4i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 1.75h8q.932 0 1.591.659T14 4v1.5q0 .932-.659 1.591t-1.591.659h-8q-.932 0-1.591-.659T1.5 5.5V4q0-.932.659-1.591T3.75 1.75M6 9H3.75q-.932 0-1.591.659T1.5 11.25v1.5q0 .932.659 1.591T3.75 15H6q2.25 0 2.25-2.25v-1.5Q8.25 9 6 9m5.75 0h8.5q2.25 0 2.25 2.25v1.5q0 2.25-2.25 2.25h-8.5Q9.5 15 9.5 12.75v-1.5Q9.5 9 11.75 9m0 7.25h-8q-.932 0-1.591.659T1.5 18.5V20q0 .932.659 1.591t1.591.659h8q.932 0 1.591-.659T14 20v-1.5q0-.932-.659-1.591t-1.591-.659m5.75 0h2.75q2.25 0 2.25 2.25V20q0 2.25-2.25 2.25H17.5q-2.25 0-2.25-2.25v-1.5q0-2.25 2.25-2.25");
}

</style>
