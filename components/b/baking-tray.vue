<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_w8szjnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baking-tray" /></template>
<style>
.n_w8szjnf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 11.5q0 .159.065.305l2 4.5q.044.099.114.182t.162.142t.196.09t.213.031h15q.109 0 .213-.031t.196-.09t.162-.142t.114-.182l2-4.499v-.001q.065-.146.065-.305q0-4.125-3-4.125q-2.714 0-2.973 3.375h-1.304Q14.714 7.375 12 7.375T9.027 10.75H7.723Q7.464 7.375 4.75 7.375q-3 0-3 4.125m16.036-.75q.196-1.875 1.464-1.875t1.464 1.875zm-11.572 0H3.286q.196-1.875 1.464-1.875t1.464 1.875M12 8.875q1.268 0 1.464 1.875h-2.928Q10.732 8.875 12 8.875");
}

</style>
