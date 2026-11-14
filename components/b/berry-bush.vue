<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzdyghg2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:berry-bush" /></template>
<style>
.bzdyghg2r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 3.25Q9.25 3.25 9.25 6q0 1.146.478 1.814q-.582.322-1.087.827q-.221.221-.407.457Q8.041 6.75 5.5 6.75q-2.75 0-2.75 2.75q0 1.506.825 2.188q-.753.561-1.235 1.456q-.873 1.62-.344 3.382t2.148 2.634q.167.09.356.09h6.75V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-1.75h6.75q.189 0 .356-.09q1.619-.872 2.148-2.634t-.344-3.382q-.482-.895-1.235-1.456q.825-.682.825-2.188q0-2.75-2.75-2.75q-2.541 0-2.734 2.348q-.186-.236-.407-.457q-.505-.505-1.087-.827q.478-.668.478-1.814q0-2.75-2.75-2.75");
}

</style>
