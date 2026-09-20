<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="doyl_6vmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-left-16-filled" /></template>
<style>
.doyl_6vmt {
  fill: currentColor;
  d: path("M9 2.75A.75.75 0 0 0 8.25 2h-5.5a.75.75 0 0 0-.75.75v5.5a.75.75 0 0 0 1.5 0V4.56l9.22 9.22a.75.75 0 0 0 1.06-1.06L4.56 3.5h3.69A.75.75 0 0 0 9 2.75");
}

</style>
