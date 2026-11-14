<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svcp433nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ancestral-tablet" /></template>
<style>
.svcp433nj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 5.5v12.86q-.172.172-.319.392l-.555.832q-.57.855-.085 1.76q.485.906 1.512.906h11.394q1.027 0 1.512-.906q.485-.905-.085-1.76l-.555-.832q-.147-.22-.319-.392V5.5q0-.095-.024-.186q-.023-.092-.069-.175q-.045-.083-.11-.152t-.144-.12Q12 1.111 6.097 4.867q-.079.051-.144.12t-.11.152q-.046.083-.069.175T5.75 5.5m1.553 12.25H7.25V5.919q4.75-2.817 9.5 0V17.75zM13 6h-2Q8.5 6 8.5 8.5V14q0 2.5 2.5 2.5h2q2.5 0 2.5-2.5V8.5Q15.5 6 13 6");
}

</style>
