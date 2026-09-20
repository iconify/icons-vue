<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqwytublu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:account-box-sharp" /></template>
<style>
.cqwytublu {
  fill: currentColor;
  d: path("M14.475 11.975Q15.5 10.95 15.5 9.5t-1.025-2.475T12 6T9.525 7.025T8.5 9.5t1.025 2.475T12 13t2.475-1.025M3 21V3h18v18zm2-2h14v-1.15q-1.35-1.325-3.137-2.087T12 15t-3.863.763T5 17.85z");
}

</style>
