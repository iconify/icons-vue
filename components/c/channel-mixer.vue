<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjpe8obzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:channel-mixer" /></template>
<style>
.vjpe8obzf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 8.25q0-2.485 1.757-4.243Q9.515 2.25 12 2.25t4.243 1.757Q18 5.765 18 8.25q0 .459-.06.894q1.127.438 2.053 1.363q1.757 1.758 1.757 4.243t-1.757 4.243t-4.243 1.757q-2.146 0-3.75-1.311q-1.604 1.311-3.75 1.311q-2.485 0-4.243-1.757Q2.25 17.235 2.25 14.75t1.757-4.243q.926-.925 2.053-1.363Q6 8.709 6 8.25");
}

</style>
