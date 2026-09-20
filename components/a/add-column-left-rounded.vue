<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swuyzr-ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-column-left-rounded" /></template>
<style>
.swuyzr-ms {
  fill: currentColor;
  d: path("M5.143 14.356Q5 14.213 5 14v-1.5H3.5q-.213 0-.356-.144T3 11.999t.144-.356t.356-.143H5V10q0-.213.144-.356t.357-.144t.356.144T6 10v1.5h1.5q.213 0 .356.144t.144.357t-.144.356t-.356.143H6V14q0 .213-.144.356t-.357.144t-.356-.144m8.3 5.644V4h5.942q.666 0 1.14.475T21 5.615v12.77q0 .666-.475 1.14t-1.14.475zm-6.827 0q-.667 0-1.141-.475T5 18.386v-1.043q0-.2.146-.332q.146-.131.354-.126q2.027 0 3.456-1.42q1.429-1.422 1.429-3.464t-1.43-3.463Q7.528 7.116 5.5 7.116q-.2 0-.35-.128T5 6.658V5.616q0-.667.475-1.141T6.615 4h5.827v16z");
}

</style>
