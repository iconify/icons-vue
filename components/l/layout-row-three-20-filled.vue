<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wab03dvhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-three-20-filled" /></template>
<style>
.wab03dvhs {
  fill: currentColor;
  d: path("M17 7V6a3 3 0 0 0-3-3H6a3 3 0 0 0-3 3v1zM3 8v4h14V8zm0 6v-1h14v1a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3");
}

</style>
