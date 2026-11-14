<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un9udpbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dry-bag" /></template>
<style>
.un9udpbwc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 2.25h9.5q1.45 0 2.475 1.025T20.25 5.75t-1.025 2.475q-.227.227-.475.404V18q0 3.75-3.75 3.75H9q-3.75 0-3.75-3.75V8.833q-1.5-.792-1.5-3.083q0-1.75.875-2.625T7.25 2.25m-.5 12.5V18q0 2.25 2.25 2.25h6q2.25 0 2.25-2.25v-3.25zm10.5-1.5V9.218q-.243.032-.5.032h-9.5q-.26 0-.5-.019v4.019z");
}

</style>
