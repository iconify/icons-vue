<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qg_gpib-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-dismiss-12-filled" /></template>
<style>
.qg_gpib-l {
  fill: currentColor;
  d: path("M4.585 1.085a2 2 0 0 1 2.83 0l3.5 3.5a2 2 0 0 1 0 2.827l-3.5 3.5a2 2 0 0 1-2.83 0l-3.499-3.5a2 2 0 0 1 0-2.828zm3.269 3.06a.5.5 0 0 0-.707 0L6 5.293L4.854 4.146a.5.5 0 0 0-.707.707l1.146 1.146l-1.146 1.147a.5.5 0 0 0 .707.707L6 6.706l1.147 1.147a.5.5 0 1 0 .707-.707L6.707 5.999l1.147-1.146a.5.5 0 0 0 0-.707");
}

</style>
