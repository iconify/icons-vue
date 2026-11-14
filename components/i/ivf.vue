<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke6zhqbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ivf" /></template>
<style>
.ke6zhqbyh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.678 2.201q.714.599.796 1.528q.081.929-.519 1.643l-.963 1.149q-.762.907-1.6.936l-4.059 5.015q-.04.049-.088.091q7.005.424 7.005 3.687V18q0 1.996-2.935 3.194Q14.728 22.25 11 22.25t-6.315-1.056Q1.75 19.996 1.75 18v-1.75q0-3.75 9.25-3.75q.624 0 1.207.017q-.047-.049-.084-.106t-.064-.119t-.041-.128q-.015-.066-.017-.134t.006-.135q.01-.067.031-.131t.054-.124t.075-.112l3.76-4.644l-.105-.085q-.714-.599-.796-1.528q-.081-.929.519-1.643l.963-1.149q1.446-1.723 3.17-.278M8 16.25q0-2 2-2t2 2t-2 2t-2-2m-4.291 2.657q.5.473 1.543.899q2.314.944 5.748.944t5.748-.944q1.043-.426 1.543-.899Q15.993 20 11 20t-7.291-1.093");
}

</style>
