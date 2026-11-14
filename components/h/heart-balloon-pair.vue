<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phtknidch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heart-balloon-pair" /></template>
<style>
.phtknidch {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 7.75q0 4.217 7.811 9.858q.048.034.1.061t.108.045t.114.027t.117.009t.117-.009t.114-.027t.108-.045t.1-.061q.292-.211.574-.42q1.324 1.877 4.037 3.912q.048.036.102.064t.111.048q.057.019.117.028t.12.01q.06 0 .12-.01q.06-.009.117-.028t.111-.048q.054-.028.102-.064q5.3-3.975 5.3-7.35q0-3.815-3.411-3.991q.411-1.042.411-2.009q0-2.152-1.512-3.604Q15.284 2.75 13.25 2.75q-2.11 0-3.25 1.197Q8.86 2.75 6.75 2.75q-2.034 0-3.488 1.396Q1.75 5.598 1.75 7.75");
}

</style>
