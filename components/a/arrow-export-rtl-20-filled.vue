<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x1nuevtha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-export-rtl-20-filled" /></template>
<style>
.x1nuevtha {
  fill: currentColor;
  d: path("M17.25 3.75a.75.75 0 0 0-.75.75v11a.75.75 0 0 0 1.5 0v-11a.75.75 0 0 0-.75-.75M15 10a.75.75 0 0 0-.75-.75H4.06l2.72-2.72a.75.75 0 0 0-1.06-1.06L1.723 9.466a.8.8 0 0 0-.156.223a.75.75 0 0 0 .156.845L5.72 14.53a.75.75 0 1 0 1.06-1.06l-2.72-2.72h10.19A.75.75 0 0 0 15 10");
}

</style>
