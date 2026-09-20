<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n51o46b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-right-16-filled" /></template>
<style>
.n51o46b8j {
  fill: currentColor;
  d: path("M7 2.75A.75.75 0 0 1 7.75 2h5.5a.75.75 0 0 1 .75.75v5.5a.75.75 0 0 1-1.5 0V4.56l-9.22 9.22a.75.75 0 0 1-1.06-1.06l9.22-9.22H7.75A.75.75 0 0 1 7 2.75");
}

</style>
