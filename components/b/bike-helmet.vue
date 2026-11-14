<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llan_cc4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bike-helmet" /></template>
<style>
.llan_cc4n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.801 12.476Q3.121 9.3 5.46 6.961Q8.169 4.253 12 4.253t6.54 2.708q2.339 2.339 2.659 5.515q1.051.486 1.051 2.024q0 2.25-2.25 2.25h-1.913Q16.979 20.5 12 20.5t-6.087-3.75H4q-2.25 0-2.25-2.25q0-1.538 1.051-2.024m16.857-.226q-.365-2.414-2.179-4.228Q15.209 5.753 12 5.753T6.521 8.022Q4.707 9.836 4.342 12.25zM12 19q3.496 0 4.486-2.25H7.514Q8.504 19 12 19");
}

</style>
