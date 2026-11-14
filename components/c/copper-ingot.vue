<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elt3vc4vj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:copper-ingot" /></template>
<style>
.elt3vc4vj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.556 9.46l.833-2.5q.57-1.71 2.372-1.71h4.478q1.802 0 2.372 1.71l.833 2.5q.316.949-.072 1.79h.867q1.802 0 2.372 1.71l.833 2.5q.404 1.214-.344 2.252t-2.028 1.038H4.928q-1.28 0-2.028-1.038t-.344-2.252l.833-2.5q.57-1.71 2.372-1.71h.867q-.388-.841-.072-1.79");
}

</style>
