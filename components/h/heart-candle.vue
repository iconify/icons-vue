<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7-q8nb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heart-candle" /></template>
<style>
.z7-q8nb5y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.438 5.125q0-1.462-1.94-3.186q-.051-.045-.109-.08t-.122-.06t-.132-.037T12 1.75t-.135.012t-.132.037t-.122.06t-.109.08Q9.563 3.663 9.563 5.125Q9.563 7 12 7q2.438 0 2.438-1.875m-9.188 6.5q0-3.375 3.375-3.375h6.75q3.375 0 3.375 3.375v7.25q0 3.375-3.375 3.375h-6.75q-3.375 0-3.375-3.375zm6.22 6.905q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l2.5-2.5q.089-.089.145-.202q.822-1.693-.576-2.951Q13.375 11.775 12 12.4q-1.375-.625-2.599.477q-1.398 1.258-.576 2.951q.056.113.145.202z");
}

</style>
