<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa69tpbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:contribution" /></template>
<style>
.qa69tpbtb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752q3.001-3.001 7.245-3.002q5.095-.044 8.206 3.992q3.112 4.037 1.771 8.955q-.04.145-.132.263q-.698 2.392-2.594 4.288Q16.246 22.25 12 22.25t-7.248-3.002T1.75 12t3.002-7.248M11.25 12V3.278q-3.144.241-5.437 2.535Q3.25 8.376 3.25 12t2.563 6.187T12 20.75t6.187-2.563q1.427-1.426 2.059-3.181l-8.442-2.282q-.059-.016-.115-.041t-.107-.06t-.095-.076t-.083-.091q-.037-.049-.066-.103t-.048-.112t-.03-.119t-.01-.122");
}

</style>
