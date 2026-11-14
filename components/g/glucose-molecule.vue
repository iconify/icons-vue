<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syfxw1bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:glucose-molecule" /></template>
<style>
.syfxw1bvg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.5Q9.5 1.5 9.5 4q0 2.092 1.75 2.433v1.666q-.183.07-.366.175l-3.75 2.143Q6 11.064 6 12.37v4.26q0 .304.062.572Q6 17.345 6 17.5q0 .069.012.136q.013.068.037.132q.025.064.061.122q.035.059.081.11t.1.093t.115.074q.061.031.127.051t.134.027q.203.187.467.338l3.75 2.143q1.116.638 2.232 0l3.75-2.143Q18 17.936 18 16.63v-4.26q0-1.306-1.134-1.953l-3.75-2.143q-.183-.105-.366-.175V6.392q.566-.173 1.018-.624Q14.5 5.036 14.5 4t-.732-1.768T12 1.5");
}

</style>
