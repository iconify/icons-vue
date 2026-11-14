<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwgya4gim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloud-cost" /></template>
<style>
.xwgya4gim {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 17.75q-2.071 0-3.536-1.464Q2 14.821 2 12.75t1.464-3.536q1.284-1.283 3.033-1.442q1.537-3.301 5.305-3.489q3.793-.19 5.651 2.984q1.884.146 3.259 1.521q1.538 1.537 1.538 3.712q0 .806-.211 1.524Q20.732 13 19 13h-2q-2.071 0-3.536 1.464q-1.375 1.376-1.459 3.286zm10-3.5q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906M17 17q.818 0 .967.669q-.467.081-.967.081h-.982Q16.134 17 17 17");
}

</style>
