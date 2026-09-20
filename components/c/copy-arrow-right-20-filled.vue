<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v0mp_tr6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-arrow-right-20-filled" /></template>
<style>
.v0mp_tr6n {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M7 11.5a3.5 3.5 0 0 0 2.004 3.164c.024.838.236 1.628.595 2.331L9.5 17h-4A2.5 2.5 0 0 1 3 14.5v-6A2.5 2.5 0 0 1 5.5 6H7zm7.854.646a.5.5 0 1 0-.707.707L15.293 14H12.5a.5.5 0 0 0 0 1h2.793l-1.146 1.146a.5.5 0 1 0 .707.707l2.002-2.001a.5.5 0 0 0 .144-.35v-.005a.5.5 0 0 0-.146-.35zM14.5 3A2.5 2.5 0 0 1 17 5.5v4.1a5.5 5.5 0 0 0-7.919 3.957A2.5 2.5 0 0 1 8 11.5v-6A2.5 2.5 0 0 1 10.5 3z");
}

</style>
