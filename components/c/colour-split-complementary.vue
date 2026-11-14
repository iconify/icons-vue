<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td-tel1pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:colour-split-complementary" /></template>
<style>
.td-tel1pz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12M9.5 7q0 1.386.769 2.004L8.812 13.01Q8.661 13 8.5 13Q6 13 6 15.5T8.5 18q2.092 0 2.433-1.75h2.134Q13.408 18 15.5 18q2.5 0 2.5-2.5T15.5 13q-.161 0-.312.01l-1.511-4.155q.046-.042.091-.087Q14.5 8.036 14.5 7t-.732-1.768T12 4.5Q9.5 4.5 9.5 7m.731 6.496q.543.436.702 1.254h2.134q.159-.818.702-1.254l-1.46-4.013Q12.158 9.5 12 9.5q-.161 0-.312-.01z");
}

</style>
