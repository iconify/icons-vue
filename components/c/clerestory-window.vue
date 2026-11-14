<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j90e73bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:clerestory-window" /></template>
<style>
.j90e73bih {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m10.423 3.815l-6.25 5.078q-.923.751-.923 1.94v8.417q0 1.036.732 1.768t1.768.732h12.5q1.036 0 1.768-.732t.732-1.768v-8.417q0-1.189-.923-1.94l-6.25-5.078q-1.577-1.282-3.154 0M8.5 11.25h7q2.25 0 2.25 2.25v.5q0 .932-.659 1.591t-1.591.659h-7q-.932 0-1.591-.659T6.25 14v-.5q0-2.25 2.25-2.25");
}

</style>
