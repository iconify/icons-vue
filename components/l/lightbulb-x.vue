<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_j08o5no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lightbulb-x" /></template>
<style>
.v_j08o5no {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.687 15.75H7.5V14.5c-2.25-1.25-4-3-4-5q0-.172.008-.343t.026-.343q.017-.171.042-.341t.059-.339q.033-.168.075-.335t.091-.331t.108-.326t.124-.321t.139-.314t.155-.307q.081-.151.169-.299q.088-.147.184-.29q.095-.143.198-.281q.102-.138.211-.271t.224-.26t.237-.249t.249-.237t.26-.224t.271-.211q.138-.103.281-.198t.29-.184q.148-.088.299-.169q.152-.081.307-.155q.155-.073.314-.139t.321-.124t.326-.108t.331-.091t.335-.075t.339-.059t.341-.042t.343-.026q.171-.008.343-.008t.343.008q.172.009.343.026t.341.042t.339.059q.168.033.335.075t.331.091t.326.108t.321.124t.314.139t.307.155t.299.169t.29.184t.281.198t.271.211t.26.224t.249.237t.237.249t.224.26t.211.271q.103.138.198.281t.184.29q.088.148.169.299q.081.152.155.307q.073.155.139.314t.124.321t.108.326t.091.331q.042.167.075.335q.034.169.059.339t.042.341t.026.343q.008.171.008.343c0 1.186-.615 2.283-1.585 3.241M8 18.75h5M9 21.5h3m3.5-6l5 5m0-5l-5 5");
}

</style>
