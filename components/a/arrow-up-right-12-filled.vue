<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="p0km72bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-right-12-filled" /></template>
<style>
.p0km72bpc {
  fill: currentColor;
  d: path("M1.22 10.78a.75.75 0 0 1 0-1.06L8.44 2.5H4.75a.75.75 0 0 1 0-1.5h5.5a.75.75 0 0 1 .75.75v5.5a.75.75 0 0 1-1.5 0V3.56l-7.22 7.22a.75.75 0 0 1-1.06 0");
}

</style>
