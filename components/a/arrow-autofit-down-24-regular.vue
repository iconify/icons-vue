<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3dxt1bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-autofit-down-24-regular" /></template>
<style>
.e3dxt1bjz {
  fill: currentColor;
  d: path("M16.75 3a.75.75 0 0 1 .75.75v14.69l1.22-1.22a.75.75 0 1 1 1.06 1.06l-2.5 2.5a.75.75 0 0 1-1.004.052l-.056-.052l-2.5-2.5a.75.75 0 0 1 1.06-1.06L16 18.44V3.75a.75.75 0 0 1 .75-.75m-3.5 1a.75.75 0 0 1 0 1.5h-7a.75.75 0 0 0-.75.75v11.5c0 .414.336.75.75.75h5a.75.75 0 0 1 0 1.5h-5A2.25 2.25 0 0 1 4 17.75V6.25A2.25 2.25 0 0 1 6.25 4z");
}

</style>
