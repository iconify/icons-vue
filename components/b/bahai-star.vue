<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qf4h0wb6v"/><circle class="rzyzgqcqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bahai-star" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qf4h0wb6v {
  d: path("m12.3 3.27l1.46 2.57q.29.52.85.31l2.77-1.03q.57-.21.46.38l-.54 2.91q-.1.59.46.79l2.78.99q.57.2.11.59l-2.28 1.88q-.46.38-.16.9l1.5 2.55q.3.52-.3.51l-2.95-.02q-.6 0-.7.59l-.5 2.91q-.1.59-.55.2l-2.25-1.91q-.46-.39-.92 0L9.29 20.3q-.45.39-.55-.2l-.5-2.91q-.1-.59-.7-.59l-2.95.02q-.6.01-.3-.51l1.5-2.55q.3-.52-.16-.9l-2.28-1.88q-.46-.39.11-.59l2.78-.99q.56-.2.46-.79L6.16 5.5q-.11-.59.46-.38l2.77 1.03q.56.21.85-.31l1.46-2.57q.3-.52.6 0");
}

.rzyzgqcqn {
  cx: 12px;
  cy: 12px;
  r: 2.25px;
}

</style>
