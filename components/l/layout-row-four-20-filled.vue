<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o6_8lub5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-four-20-filled" /></template>
<style>
.o6_8lub5t {
  fill: currentColor;
  d: path("M3 14a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3zm14-1v-2.5H3V13zm0-6v2.5H3V7zm0-1a3 3 0 0 0-3-3H6a3 3 0 0 0-3 3z");
}

</style>
