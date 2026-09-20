<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oa-1rkmpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-add-above-16-regular" /></template>
<style>
.oa-1rkmpb {
  fill: currentColor;
  d: path("M13.5 6a.5.5 0 0 1 .5.5v5a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5v-5a.5.5 0 0 1 .5-.5zM3 11.5A1.5 1.5 0 0 0 4.5 13h7a1.5 1.5 0 0 0 1.5-1.5V7H3zM13.5 2a.5.5 0 0 1 0 1h-11a.5.5 0 0 1 0-1z");
}

</style>
