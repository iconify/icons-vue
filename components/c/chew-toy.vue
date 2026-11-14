<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk0of_bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chew-toy" /></template>
<style>
.nk0of_bcw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.812 12q.974 2.501-.388 4.885q-1.365 2.389-4.022 2.817Q14.713 21.75 12 21.75t-4.402-2.048q-2.657-.428-4.022-2.817Q2.214 14.501 3.188 12q-.974-2.501.388-4.885q1.365-2.389 4.022-2.817Q9.287 2.25 12 2.25t4.402 2.048q2.657.428 4.022 2.817q1.362 2.384.388 4.885M6.75 12q0 2.175 1.538 3.712Q9.825 17.25 12 17.25t3.712-1.538Q17.25 14.175 17.25 12t-1.538-3.712Q14.175 6.75 12 6.75T8.288 8.288Q6.75 9.825 6.75 12");
}

</style>
