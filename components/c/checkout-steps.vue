<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj3e6b0fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:checkout-steps" /></template>
<style>
.qj3e6b0fv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.25 12q0-3 3-3q2.598 0 2.946 2.25h1.858Q9.402 9 12 9t2.946 2.25h1.858Q17.152 9 19.75 9q3 0 3 3t-3 3q-2.598 0-2.946-2.25h-1.858Q14.598 15 12 15t-2.946-2.25H7.196Q6.848 15 4.25 15q-1.243 0-2.121-.879Q1.25 13.243 1.25 12");
}

</style>
