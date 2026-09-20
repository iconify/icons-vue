<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs7z7bcig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:equal-circle-24-filled" /></template>
<style>
.bs7z7bcig {
  fill: currentColor;
  d: path("M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12s4.477 10 10 10s10-4.477 10-10m-5.748-1.5h-8.5a.75.75 0 0 1 0-1.5h8.5a.75.75 0 0 1 0 1.5m0 4.5h-8.5a.75.75 0 0 1 0-1.5h8.5a.75.75 0 0 1 0 1.5");
}

</style>
