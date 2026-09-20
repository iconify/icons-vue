<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ohnzzloer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-export-rtl-16-regular" /></template>
<style>
.ohnzzloer {
  fill: currentColor;
  d: path("M14.5 3a.5.5 0 0 0-.5.5V12a.5.5 0 0 0 1 0V3.5a.5.5 0 0 0-.5-.5m-9.146.646a.5.5 0 0 0-.708 0l-3.5 3.5a.5.5 0 0 0 0 .708l3.5 3.5a.5.5 0 0 0 .708-.708L2.707 8H11.5a.5.5 0 0 0 0-1H2.707l2.647-2.646a.5.5 0 0 0 0-.708");
}

</style>
