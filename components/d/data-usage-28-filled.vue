<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="d9zutlb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-usage-28-filled" /></template>
<style>
.d9zutlb9c {
  fill: currentColor;
  d: path("M6.75 3A3.75 3.75 0 0 0 3 6.75v14.5A3.75 3.75 0 0 0 6.75 25h14.5A3.75 3.75 0 0 0 25 21.25V6.75A3.75 3.75 0 0 0 21.25 3zm2.75 8.75v7.5a.75.75 0 0 1-1.5 0v-7.5a.75.75 0 0 1 1.5 0M14 14a.75.75 0 0 1 .75.75v4.5a.75.75 0 0 1-1.5 0v-4.5A.75.75 0 0 1 14 14m6-5.25v10.5a.75.75 0 0 1-1.5 0V8.75a.75.75 0 0 1 1.5 0");
}

</style>
