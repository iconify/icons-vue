<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf-xrzbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flat-mop" /></template>
<style>
.lf-xrzbmi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.406 16.75q-.789-1.152-1.633-1.64l9.313-11.641q.046-.058.08-.124q.034-.065.054-.136q.021-.071.027-.145q.007-.073-.002-.147q-.008-.073-.03-.144t-.058-.135t-.083-.121t-.105-.103q-.117-.093-.26-.134t-.292-.025t-.279.088t-.224.188l-9.8 12.251q-1.323.221-2.52 1.968H4.75q-1.036 0-1.768.732T2.25 19.25t.732 1.768t1.768.732h9.5q1.036 0 1.768-.732t.732-1.768t-.732-1.768t-1.768-.732zm-1.927 0q-.519-.5-.979-.5t-.979.5z");
}

</style>
