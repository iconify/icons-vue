<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmfjkwjer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:brand-awareness" /></template>
<style>
.lmfjkwjer {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12M7.7 7.15L6.617 8.594q-.268.357-.397.71q-.104.042-.192.113q-.087.07-.15.163q-.062.093-.095.201q-.033.107-.033.219q0 .059.009.116t.027.114q.018.056.044.108q.027.052.061.1q.034.047.075.089t.088.076t.099.062t.108.046q.15.345.438.686l3.584 4.235q.674.796 1.717.796t1.718-.797l3.583-4.233q.288-.342.438-.687q.056-.019.108-.046t.099-.062t.088-.076t.075-.089t.061-.1t.044-.108t.027-.114q.009-.057.009-.116q0-.112-.033-.219q-.033-.108-.095-.201q-.063-.093-.15-.163q-.088-.071-.192-.113q-.129-.353-.397-.71L16.3 7.15q-.675-.9-1.8-.9h-5q-1.125 0-1.8.9");
}

</style>
