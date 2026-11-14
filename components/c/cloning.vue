<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfsb6icty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloning" /></template>
<style>
.tfsb6icty {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.02 4.02Q1.75 6.29 1.75 9.5t2.27 5.48q2.264 2.264 5.463 2.27q.42 1.492 1.598 2.669q1.83 1.831 4.419 1.831t4.419-1.831T21.75 15.5t-1.831-4.419q-1.177-1.178-2.669-1.598q-.006-3.199-2.27-5.463q-2.27-2.27-5.48-2.27T4.02 4.02");
}

</style>
