<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q12ccdb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:colour-temperature" /></template>
<style>
.q12ccdb7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.025 17H8v-1.5C5.5 14 4 11.5 4 9q0-.172.008-.343t.026-.343q.017-.171.042-.341t.059-.339q.033-.168.075-.335t.091-.331t.108-.326t.124-.321t.139-.314t.155-.307q.081-.151.169-.299q.088-.147.184-.29q.095-.143.198-.281q.102-.138.211-.271t.224-.26t.237-.249t.249-.237t.26-.224t.271-.211t.281-.198t.29-.184t.299-.169t.307-.155t.314-.139t.321-.124t.326-.108t.331-.091t.335-.075t.339-.059t.341-.042t.343-.026Q10.828 2 11 2t.343.008q.172.009.343.026t.341.042t.339.059q.168.033.335.075t.331.091t.326.108t.321.124t.314.139t.307.155t.299.169t.29.184t.281.198t.271.211t.26.224t.249.237t.237.249t.224.26t.211.271t.198.281t.184.29t.169.299t.155.307q.073.155.139.314t.124.321t.108.326t.091.331q.042.167.075.335q.034.169.059.339t.042.341t.026.343Q18 8.828 18 9q0 .628-.123 1.249M8.5 20.5h3.4m3.6-3.5v-2.75a1.25 1.25 0 0 1 2.5 0V17a2.25 2.25 0 1 1-2.5 0Z");
}

</style>
