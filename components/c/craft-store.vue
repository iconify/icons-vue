<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o19qysbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:craft-store" /></template>
<style>
.o19qysbgk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.311 6.205q-.061.141-.061.295q.001 2.999 3 2.999q1.499 0 2.249-.75q.75.751 2.251.751T12 8.75q.75.75 2.25.75t2.251-.751q.75.749 2.249.749q2.998 0 3-2.997v-.022zM11.25 18.5q0-.93-.491-1.656L12 15.711l1.131 1.033q-.381.687-.381 1.756q0 3 3 3t3-3t-3-3q-.866 0-1.483.25l-1.155-1.054l2.894-2.642q.11-.101.173-.236t.07-.284t-.044-.289t-.151-.251q-.101-.11-.236-.173t-.284-.07t-.289.044t-.251.151L12 13.68l-2.994-2.734q-.11-.1-.251-.151q-.14-.051-.289-.044t-.284.07t-.236.173q-.05.055-.088.118t-.063.133t-.036.142t-.008.147t.021.146t.049.138t.075.127q.044.059.098.109l2.894 2.642l-1.245 1.136q-.628-.333-1.393-.333q-1.243 0-2.122.879T5.25 18.5t.878 2.122q.879.879 2.122.879t2.122-.879t.878-2.122");
}

</style>
