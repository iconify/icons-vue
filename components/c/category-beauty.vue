<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c68wwnh0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-beauty" /></template>
<style>
.c68wwnh0l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.591 11.409q-.272-.272-.591-.432V3.5q0-.227-.126-.416q-.041-.061-.093-.114q-.052-.052-.114-.093q-.061-.041-.129-.07q-.068-.028-.141-.042t-.146-.015q-.074 0-.147.014q-.072.015-.14.043t-.13.069l-4.5 3q-.077.051-.139.12q-.063.068-.106.15q-.044.082-.066.172T9 6.5v4.396Q7.75 11.323 7.75 13v1.5q0 .475.1.85q-1.6.4-1.6 2.4v2q0 1.036.732 1.768t1.768.732h6.5q1.036 0 1.768-.732t.732-1.768v-2q0-2.033-1.654-2.413q.154-.387.154-.837V13q0-.932-.659-1.591M13.5 10.75h-3V6.901l3-2z");
}

</style>
