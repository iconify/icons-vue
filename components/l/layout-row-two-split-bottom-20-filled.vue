<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="raiev2bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-two-split-bottom-20-filled" /></template>
<style>
.raiev2bfv {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v3.5h14V6a3 3 0 0 0-3-3zm11 7.5h-6.5V17H14a3 3 0 0 0 3-3zm-7.5 0H3V14a3 3 0 0 0 3 3h3.5z");
}

</style>
