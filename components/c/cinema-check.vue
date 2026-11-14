<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1og4feoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cinema-check" /></template>
<style>
.x1og4feoq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.762 17H2.5v-4q.111 0 .22-.011q.11-.011.219-.032q.108-.022.214-.054t.208-.075t.199-.094t.19-.114q.091-.061.177-.131t.163-.148q.078-.079.148-.164q.071-.085.132-.177t.113-.19q.052-.097.095-.199q.042-.102.074-.208t.054-.214q.021-.109.032-.219q.011-.109.011-.22t-.011-.22t-.032-.219q-.022-.108-.054-.214t-.074-.208q-.043-.102-.095-.199T4.37 9.5t-.132-.177q-.07-.085-.148-.164q-.078-.078-.163-.148T3.75 8.88t-.19-.114q-.097-.052-.199-.094t-.208-.075t-.214-.054q-.109-.021-.219-.032Q2.611 8.5 2.5 8.5v-4h18v4q-.11 0-.22.011t-.219.032q-.108.022-.214.054t-.208.075t-.199.094t-.19.114q-.091.061-.177.131t-.163.148t-.148.164t-.132.177t-.113.19q-.052.097-.095.199q-.042.102-.074.208t-.054.214t-.032.219q-.011.109-.011.22q0 .184.03.366t.089.357q.06.174.146.337q.087.163.2.309q.112.146.246.272q.135.127.288.229t.321.179q.168.076.346.124M14.75 18l2 2L21 15.75");
}

</style>
