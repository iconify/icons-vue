<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qbu_rqk0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-right-dashes-12-filled" /></template>
<style>
.qbu_rqk0k {
  fill: currentColor;
  d: path("M9.5 7.25a.75.75 0 0 0 1.5 0v-5.5a.75.75 0 0 0-.75-.75h-5.5a.75.75 0 0 0 0 1.5h3.69L6.97 3.97a.75.75 0 0 0 1.06 1.06L9.5 3.56zm-3.22-.47a.75.75 0 0 0-1.06-1.06L3.97 6.97a.75.75 0 0 0 1.06 1.06zm-3 3a.75.75 0 0 0-1.06-1.06L.97 9.97a.75.75 0 1 0 1.06 1.06z");
}

</style>
