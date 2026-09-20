<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pnlyjpb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-left-12-filled" /></template>
<style>
.pnlyjpb5e {
  fill: currentColor;
  d: path("M7.53 2.22a.75.75 0 0 1 0 1.06L4.81 6l2.72 2.72a.75.75 0 0 1-1.06 1.06L3.22 6.53a.75.75 0 0 1 0-1.06l3.25-3.25a.75.75 0 0 1 1.06 0");
}

</style>
