<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gllufzigv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-down-12-filled" /></template>
<style>
.gllufzigv {
  fill: currentColor;
  d: path("M11 6A5 5 0 1 1 1 6a5 5 0 0 1 10 0m-2.646.098a.5.5 0 0 0-.708 0L6.5 7.244V3.5a.5.5 0 0 0-1 0v3.744L4.354 6.098a.5.5 0 1 0-.708.707l2 2a.5.5 0 0 0 .708 0l2-2a.5.5 0 0 0 0-.707");
}

</style>
