<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og8rwpauv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coffee-tamper" /></template>
<style>
.og8rwpauv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.658 12.399q-.158-.849-.588-2.1q-.82-2.391-.82-3.799q0-1.968 1.391-3.359T12 1.75t3.359 1.391T16.75 6.5q0 1.408-.82 3.799q-.43 1.251-.588 2.1q5.408.546 5.408 3.101v3q0 3.25-8.75 3.25T3.25 18.5v-3q0-2.555 5.408-3.101m5.182-.109q-.866-.04-1.84-.04t-1.84.04q-.172-1.025-.671-2.478Q8.75 7.658 8.75 6.5q0-3.25 3.25-3.25t3.25 3.25q0 1.158-.739 3.312q-.499 1.453-.671 2.478m5.41 6.21v-.866Q17.127 18.75 12 18.75t-7.25-1.116v.866q0 .484 1.817 1.052q2.234.698 5.433.698t5.433-.698q1.817-.568 1.817-1.052");
}

</style>
