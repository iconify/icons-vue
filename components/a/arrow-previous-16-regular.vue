<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p-7n626zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-previous-16-regular" /></template>
<style>
.p-7n626zd {
  fill: currentColor;
  d: path("M12.354 3.854a.5.5 0 0 0-.708-.708l-4.5 4.5a.5.5 0 0 0 0 .708l4.5 4.5a.5.5 0 0 0 .708-.708L8.207 8zM4 3.5a.5.5 0 0 1 1 0v9a.5.5 0 0 1-1 0z");
}

</style>
