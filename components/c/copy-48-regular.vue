<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p9h7stjbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-48-regular" /></template>
<style>
.p9h7stjbh {
  fill: currentColor;
  d: path("M17 16.5h-4.75a3.75 3.75 0 0 0-3.75 3.75v15.5a3.75 3.75 0 0 0 3.75 3.75h10.5a3.75 3.75 0 0 0 3.741-3.5h2.503a6.25 6.25 0 0 1-6.244 6h-10.5A6.25 6.25 0 0 1 6 35.75v-15.5A6.25 6.25 0 0 1 12.25 14H17zM35.75 6A6.25 6.25 0 0 1 42 12.25v15.5A6.25 6.25 0 0 1 35.75 34h-10.5A6.25 6.25 0 0 1 19 27.75v-15.5A6.25 6.25 0 0 1 25.25 6zm-10.5 2.5a3.75 3.75 0 0 0-3.75 3.75v15.5a3.75 3.75 0 0 0 3.75 3.75h10.5a3.75 3.75 0 0 0 3.75-3.75v-15.5a3.75 3.75 0 0 0-3.75-3.75z");
}

</style>
