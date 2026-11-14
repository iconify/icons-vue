<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szy36l87c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:anticline" /></template>
<style>
.szy36l87c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.863 8.089Q1.75 12.349 1.75 19.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-7.151-3.113-11.411Q16.24 4.125 12 4.125T4.863 8.089m.896 10.661h-2.5q.152-6.132 2.815-9.776Q8.521 5.625 12 5.625t5.926 3.349q2.663 3.644 2.815 9.776h-2.5q-.121-4.812-1.808-7.777Q14.671 7.875 12 7.875t-4.433 3.098Q5.88 13.938 5.759 18.75m9.37-7.035q1.496 2.628 1.611 7.035h-2.496Q14.135 12 12 12t-2.244 6.75H7.26q.115-4.407 1.611-7.035q1.331-2.34 3.129-2.34t3.129 2.34M12 13.5q.702 0 .747 5.25h-1.494q.045-5.25.747-5.25");
}

</style>
