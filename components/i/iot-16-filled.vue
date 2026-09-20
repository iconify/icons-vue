<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mr7jz_tdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:iot-16-filled" /></template>
<style>
.mr7jz_tdv {
  fill: currentColor;
  d: path("M12 3.5a1.5 1.5 0 0 1-1.75 1.48l-.623 1.122c.48.412.803 1.004.863 1.672l.66.073a1.5 1.5 0 1 1-.111.994l-.659-.073a2.5 2.5 0 0 1-1.13 1.398l.277.834a1.5 1.5 0 1 1-.949.316l-.278-.834a2.5 2.5 0 0 1-2.199-.855l-1.122.623q.021.122.021.25a1.5 1.5 0 1 1-.507-1.124l1.122-.623a2.5 2.5 0 0 1 .3-2.132l-.768-.767a1.5 1.5 0 1 1 .707-.707l.767.767a2.49 2.49 0 0 1 2.132-.299l.623-1.122A1.5 1.5 0 1 1 12 3.5");
}

</style>
