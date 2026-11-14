<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws3s-3_jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drum-practice" /></template>
<style>
.ws3s-3_jj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.502 3.061l3.345 2.973Q3.25 6.782 3.25 9.5V16q0 1.919 2.798 3.149Q8.552 20.25 12 20.25t5.952-1.101Q20.75 17.919 20.75 16V9.5q0-2.718-4.597-3.466l3.345-2.973q.112-.1.177-.234t.074-.283t-.04-.29t-.148-.252t-.234-.177t-.283-.074t-.29.04t-.252.148l-4.36 3.875Q13.146 5.75 12 5.75t-2.142.064l-4.36-3.875q-.111-.099-.252-.148t-.29-.04t-.283.074t-.234.177q-.049.055-.086.119q-.037.063-.062.133q-.024.07-.034.143t-.006.147t.023.145t.051.138t.077.126q.045.058.1.108M12 13.25q5.127 0 7.25-1.288V16q0 .94-1.902 1.776q-2.215.974-5.348.974t-5.348-.974Q4.75 16.94 4.75 16v-4.038Q6.873 13.25 12 13.25");
}

</style>
