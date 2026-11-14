<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4oc2qjwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gasometer" /></template>
<style>
.r4oc2qjwj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 9.5q0-3.003 2.123-5.127T12 2.25t5.127 2.123Q19.25 6.497 19.25 9.5q0 2.859-1.925 4.921l1.898 6.88q.02.071.025.144q.005.074-.004.147q-.009.074-.032.144t-.06.134t-.084.12q-.049.056-.107.102t-.124.078t-.138.053q-.071.02-.144.025q-.074.005-.147-.004q-.074-.009-.144-.032t-.134-.06t-.12-.084q-.056-.049-.102-.107t-.078-.124t-.053-.138l-.814-2.949H7.037l-.814 2.949q-.04.144-.131.262q-.092.118-.222.191t-.278.092t-.291-.021q-.072-.02-.138-.053t-.124-.078t-.107-.102t-.084-.12q-.037-.064-.06-.134t-.032-.144t-.004-.147t.025-.144l1.898-6.88Q4.75 12.359 4.75 9.5m2.7 7.75h9.1l-.479-1.736Q14.291 16.75 12 16.75t-4.071-1.236z");
}

</style>
