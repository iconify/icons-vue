<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cwkil7uuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-up-16-regular" /></template>
<style>
.cwkil7uuk {
  fill: currentColor;
  d: path("M3.146 10.354a.5.5 0 0 0 .708 0L8 6.207l4.146 4.147a.5.5 0 0 0 .708-.708l-4.5-4.5a.5.5 0 0 0-.708 0l-4.5 4.5a.5.5 0 0 0 0 .708");
}

</style>
