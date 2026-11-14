<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha1_vv77m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:comment-star" /></template>
<style>
.ha1_vv77m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.384 20.313q3.993 2.426 8.36.573q4.527-1.922 5.465-6.75T18.67 5.83q-3.478-3.477-8.306-2.539t-6.75 5.465q-1.853 4.367.573 8.36l-.908 3.178q-.059.206 0 .412q.02.071.054.137q.034.065.08.123t.102.106t.121.084q.064.035.135.058q.07.023.143.031q.074.009.147.002q.074-.006.145-.026zm5.949-11.805l.312.633q.175.353.565.41l.698.102q.914.132 1.2 1.011t-.375 1.525l-.505.493q-.283.276-.217.664l.119.695q.156.911-.591 1.454q-.748.544-1.566.114l-.625-.328q-.349-.184-.698 0l-.625.328q-.818.43-1.566-.114q-.747-.543-.591-1.454l.119-.695q.066-.388-.216-.664l-.506-.493q-.661-.646-.375-1.525t1.201-1.011l.697-.102q.39-.057.565-.41l.313-.633q.408-.829 1.333-.829q.924 0 1.333.829");
}

</style>
