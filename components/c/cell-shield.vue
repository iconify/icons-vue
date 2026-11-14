<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg4ujn63b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cell-shield" /></template>
<style>
.pg4ujn63b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.313 4.313Q1.75 6.876 1.75 10.5t2.563 6.187T10.5 19.25q.674 0 1.311-.089Q11.5 18.17 11.5 17v-3q0-.152.023-.302t.068-.295t.112-.281t.153-.261t.191-.235q.104-.111.224-.204t.252-.167q.133-.074.275-.128l4-1.5q.168-.063.345-.095t.357-.032t.357.032t.345.095l1.035.388q.013-.255.013-.515q0-3.624-2.563-6.187T10.5 1.75T4.313 4.313M6 9.5Q6 6 9.5 6T13 9.5T9.5 13T6 9.5m11.763 2.298l4 1.5q.108.04.198.11t.155.165t.1.203t.034.224v3q0 3.957-4.513 5.462q-.115.038-.237.038t-.237-.038Q12.75 20.957 12.75 17v-3q0-.115.034-.224t.1-.203t.155-.165t.198-.11l4-1.5q.127-.048.263-.048t.263.048M14.25 14.52V17q0 2.777 3.25 3.956q3.25-1.179 3.25-3.956v-2.48l-3.25-1.219zm2.437 2.167q.853-.852 1.422-1.823l-.609-.228l-2 .75V17q0 .337.076.641q.579-.421 1.111-.954");
}

</style>
