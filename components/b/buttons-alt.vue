<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx5ozoois"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:buttons-alt" /></template>
<style>
.qx5ozoois {
  fill: currentColor;
  d: path("M4 18q-.825 0-1.412-.587T2 16V8q0-.825.588-1.412T4 6h16q.825 0 1.413.588T22 8v8q0 .825-.587 1.413T20 18zm3.25-3h1.5v-2.25H11v-1.5H8.75V9h-1.5v2.25H5v1.5h2.25z");
}

</style>
