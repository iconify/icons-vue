<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="op2xt-ivf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-add-above-16-filled" /></template>
<style>
.op2xt-ivf {
  fill: currentColor;
  d: path("M13.5 6a.5.5 0 0 1 .5.5v5a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5v-5a.5.5 0 0 1 .5-.5zm0-4a.5.5 0 0 1 0 1h-11a.5.5 0 0 1 0-1z");
}

</style>
