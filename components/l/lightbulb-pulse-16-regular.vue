<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hzb6lgbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lightbulb-pulse-16-regular" /></template>
<style>
.hzb6lgbei {
  fill: currentColor;
  d: path("M10.5 9h1.24a4.5 4.5 0 0 1-.586.708a.66.66 0 0 0-.18.286l-.791 2.9A1.5 1.5 0 0 1 8.735 14H7.263a1.5 1.5 0 0 1-1.448-1.105l-.79-2.9a.65.65 0 0 0-.181-.287A4.5 4.5 0 0 1 4.258 9H5.5l.047-.002c.192.19.36.435.442.733L6.336 11h3.326l.347-1.269c.081-.298.25-.545.442-.735c.016 0 .033.004.049.004m-3.72 3.632a.5.5 0 0 0 .483.368h1.472a.5.5 0 0 0 .483-.368L9.39 12H6.608zM6.506 4.5a.5.5 0 0 1 .462.324l1.096 2.927l.989-1.975a.5.5 0 0 1 .863-.053L10.768 7h1.482a.5.5 0 0 1 0 1H10.5a.5.5 0 0 1-.416-.223l-.522-.783l-1.115 2.23a.5.5 0 0 1-.915-.048L6.484 6.383l-.52 1.303A.5.5 0 0 1 5.5 8H3.75a.5.5 0 0 1 0-1h1.412l.874-2.186l.033-.068a.5.5 0 0 1 .437-.246M7.999 2a4.5 4.5 0 0 1 4.472 4h-1.008a3.5 3.5 0 0 0-6.897-.19q-.029.095-.045.19h-.994A4.5 4.5 0 0 1 8 2");
}

</style>
