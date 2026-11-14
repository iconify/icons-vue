<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bzjabiy8b"/><path class="d66saq7ze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:keep-cool" /></template>
<style>
.bzjabiy8b {
  d: path("M12.614 21.159q-.174.065-.357.093q-.184.027-.369.015q-.186-.012-.364-.063q-.179-.05-.343-.137l-6.75-3.574q-.105-.056-.201-.125t-.183-.151q-.086-.081-.161-.174q-.074-.092-.135-.194t-.109-.211q-.046-.109-.078-.223q-.032-.115-.048-.233q-.016-.117-.016-.236V8.054q0-.119.016-.236q.016-.118.048-.233q.032-.114.078-.223q.047-.109.109-.211q.061-.102.135-.194t.161-.174t.183-.151t.201-.125l6.75-3.574q.189-.1.397-.152T12 2.73t.422.051q.208.052.397.152l6.75 3.574q.105.056.201.125t.183.151q.086.081.161.174q.074.092.135.194t.109.211q.046.109.078.223q.032.115.048.233q.016.117.016.236v4.357");
}

.d66saq7ze {
  d: path("m3.5 7l8.5 4.5L20.5 7M12 11.5v10m6-7v7m-3-5.25l6 3.5m-6 0l6-3.5M16.5 15l1.5 1.5l1.5-1.5m-3 6l1.5-1.5l1.5 1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
