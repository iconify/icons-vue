<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_h33rq3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:life-beneficiary-add" /></template>
<style>
.s_h33rq3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm-3 14q0-.172.008-.343t.026-.343q.017-.171.042-.341t.059-.339t.075-.335t.091-.331t.108-.326t.124-.321t.139-.314t.155-.307q.081-.151.169-.299q.088-.147.184-.29q.095-.143.198-.281q.102-.138.211-.271t.224-.26t.237-.249t.249-.237t.26-.224t.271-.211t.281-.198t.29-.184t.299-.169t.307-.155q.155-.073.314-.139t.321-.124t.326-.108t.331-.091t.335-.075t.339-.059t.341-.042t.343-.026Q10.328 14 10.5 14q.524 0 1.043.078t1.02.233q.501.154.973.382q.473.227.906.522M18 15v6m-3-3h6");
}

</style>
