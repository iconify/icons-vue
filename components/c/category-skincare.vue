<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6uk2ylhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-skincare" /></template>
<style>
.s6uk2ylhu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 5q1.744 0 1.967 1.902Q13.109 6.75 12 6.75t-1.967.152Q10.256 5 12 5m.209-2.687q-.675.451-.875 1.227q-2.79.355-2.833 3.85q-.422.22-.719.517q-1.118 1.118-.726 3.343H4.75q-.828 0-1.414.586T2.75 13.25q0 1.732 1.5 1.964V18.5q0 3.75 3.25 3.75h9q3.25 0 3.25-3.75v-3.286q1.5-.232 1.5-1.964q0-2-2-2h-2.306q.392-2.225-.726-3.343q-.297-.297-.719-.517q-.04-3.282-2.503-3.795q.021-.018.045-.033q.304-.203.777-.084q.145.036.292.014q.148-.022.276-.099t.217-.197q.088-.119.125-.264q.036-.145.014-.292q-.022-.148-.099-.276t-.197-.217q-.119-.088-.264-.125q-1.117-.279-1.973.291m2.948 6.655q.625.625.26 2.282H8.583q-.365-1.657.26-2.282Q9.561 8.25 12 8.25t3.157.718M5.75 15.25h12.5v3.25q0 2.25-1.75 2.25h-9q-1.75 0-1.75-2.25z");
}

</style>
