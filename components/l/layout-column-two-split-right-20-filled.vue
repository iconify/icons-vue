<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="se_wrsbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-column-two-split-right-20-filled" /></template>
<style>
.se_wrsbly {
  fill: currentColor;
  d: path("M14 17h-3.5v-6.5H17V14a3 3 0 0 1-3 3m3-7.5h-6.5V3H14a3 3 0 0 1 3 3zM6 3h3.5v14H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3");
}

</style>
