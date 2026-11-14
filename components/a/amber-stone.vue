<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr0ftlxet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:amber-stone" /></template>
<style>
.kr0ftlxet {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.838 6.446Q1.75 8.722 1.75 12t3.088 5.554Q7.818 19.75 12 19.75t7.162-2.196Q22.25 15.278 22.25 12t-3.088-5.554Q16.182 4.25 12 4.25T4.838 6.446m5.157.099q.069-.025.142-.036q.073-.012.147-.008q.074.003.146.021q.071.018.138.049t.127.075q.059.044.109.098t.088.118q.038.063.063.133q.051.14.044.289t-.07.284t-.173.236q-.11.1-.251.151q-1.872.678-2.55 2.55q-.051.141-.151.251q-.101.11-.236.173t-.284.07t-.289-.044q-.07-.025-.133-.063t-.118-.088q-.054-.05-.098-.109q-.044-.06-.075-.127t-.049-.138t-.021-.146t.008-.147t.036-.142q.917-2.533 3.45-3.45");
}

</style>
