<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg2v8_bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bounty" /></template>
<style>
.gg2v8_bzw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 10.5q0-3.624 2.563-6.187T10.5 1.75t6.187 2.563T19.25 10.5q0 1.32-.34 2.5H17q-2.071 0-3.536 1.464Q12 15.929 12 18q0 .581.115 1.114q-.779.136-1.615.136q-3.624 0-6.187-2.563T1.75 10.5m5.391-3.359Q5.75 8.532 5.75 10.5t1.391 3.359T10.5 15.25t3.359-1.391T15.25 10.5t-1.391-3.359T10.5 5.75T7.141 7.141M17 14.25q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906");
}

</style>
