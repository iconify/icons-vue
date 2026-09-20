<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fnr5atb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lightbulb-pulse-16-filled" /></template>
<style>
.fnr5atb5u {
  fill: currentColor;
  d: path("M10.183 12.895A1.5 1.5 0 0 1 8.735 14H7.263a1.5 1.5 0 0 1-1.448-1.105L5.571 12h4.856zM6.595 9.526a1.5 1.5 0 0 0 2.746.145l.43-.861c.22.122.469.19.728.19h1.241a4.5 4.5 0 0 1-.586.708a.66.66 0 0 0-.18.286L10.699 11H5.3l-.275-1.006a.65.65 0 0 0-.18-.286A4.5 4.5 0 0 1 4.258 9h1.241c.294 0 .572-.087.809-.238zM6.505 4.5a.5.5 0 0 1 .463.324l1.096 2.927l.989-1.975a.5.5 0 0 1 .863-.053L10.768 7h1.482a.5.5 0 0 1 0 1H10.5a.5.5 0 0 1-.416-.223l-.522-.783l-1.115 2.23a.5.5 0 0 1-.915-.048L6.484 6.383l-.52 1.303A.5.5 0 0 1 5.5 8H3.75a.5.5 0 0 1 0-1h1.412l.874-2.186l.033-.068a.5.5 0 0 1 .437-.246M8 2a4.5 4.5 0 0 1 4.472 4H11.3l-.554-.832a1.5 1.5 0 0 0-2.55.09l-.294-.784a1.5 1.5 0 0 0-2.75-.136l-.047.105L4.483 6h-.956A4.5 4.5 0 0 1 8 2");
}

</style>
