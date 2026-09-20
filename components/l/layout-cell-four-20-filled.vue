<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dhe1kmyoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-cell-four-20-filled" /></template>
<style>
.dhe1kmyoh {
  fill: currentColor;
  d: path("M14 17h-3.5v-6.5H17V14a3 3 0 0 1-3 3m3-7.5h-6.5V3H14a3 3 0 0 1 3 3zm-7.5 0V3H6a3 3 0 0 0-3 3v3.5zm-6.5 1V14a3 3 0 0 0 3 3h3.5v-6.5z");
}

</style>
