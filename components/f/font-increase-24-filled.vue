<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btl9e7d8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:font-increase-24-filled" /></template>
<style>
.btl9e7d8d {
  fill: currentColor;
  d: path("M16.625 5.78a1 1 0 0 1-1.25-1.56l2.5-2a1 1 0 0 1 1.25 0l2.5 2a1 1 0 0 1-1.25 1.56L18.5 4.28zm-3.706-1.174a1 1 0 0 0-1.838 0l-6 14a1 1 0 0 0 1.838.788L8.803 15h6.395l1.883 4.394a1 1 0 0 0 1.838-.788zM12 7.54L14.34 13H9.66z");
}

</style>
