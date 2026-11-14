<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezpy_tb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:life-critical-illness" /></template>
<style>
.ezpy_tb2x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.989 17.08q2.305 2.146 4.62 3.56q.088.054.188.082q.099.028.203.028t.203-.028t.188-.082q2.315-1.414 4.62-3.56q2.394-2.227 3.578-4.33h-5.654l-1.784 3.122q-.119.208-.337.309q-.135.062-.284.068t-.289-.045t-.25-.153t-.172-.237l-2.438-5.283l-1.257 1.885q-.051.077-.12.139q-.068.063-.15.106q-.082.044-.172.066t-.182.023H3.411q1.184 2.103 3.578 4.33m-4.275-5.83q-.464-1.274-.464-2.5q0-2.298 1.601-3.899T7.75 3.25q2.621 0 4.25 1.953q1.629-1.953 4.25-1.953q2.298 0 3.899 1.601T21.75 8.75q0 1.226-.464 2.5H14.5q-.099 0-.195.026t-.181.075q-.086.05-.156.12q-.07.071-.119.157l-1.278 2.236l-2.39-5.178q-.089-.193-.265-.31q-.061-.041-.13-.069q-.068-.028-.14-.043t-.147-.014t-.146.015q-.073.014-.141.042t-.129.07t-.114.093q-.052.053-.093.114L7.099 11.25z");
}

</style>
