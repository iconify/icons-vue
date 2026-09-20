<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="jf42qf41q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-counterclockwise-28-regular" /></template>
<style>
.jf42qf41q {
  fill: currentColor;
  d: path("M23.5 14A9.5 9.5 0 0 0 14 4.5a9.47 9.47 0 0 0-6.928 3H9.75a.75.75 0 0 1 0 1.5h-4A.75.75 0 0 1 5 8.25v-4a.75.75 0 0 1 1.5 0v1.703A10.96 10.96 0 0 1 14 3c6.075 0 11 4.925 11 11s-4.925 11-11 11S3 20.075 3 14q0-.68.08-1.34a.75.75 0 1 1 1.49.18q-.07.57-.07 1.16a9.5 9.5 0 0 0 19 0");
}

</style>
