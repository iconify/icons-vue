<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ac-1p8enr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:apps-add-in-20-regular" /></template>
<style>
.ac-1p8enr {
  fill: currentColor;
  d: path("M14.5 2.5a.5.5 0 0 1 .5.5v2h2a.5.5 0 0 1 0 1h-2v2a.5.5 0 0 1-1 0V6h-2a.5.5 0 0 1 0-1h2V3a.5.5 0 0 1 .5-.5M3 5a2 2 0 0 1 2-2h3.5a2 2 0 0 1 2 2v4.5H15a2 2 0 0 1 2 2V15a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2zm6.5 4.5V5a1 1 0 0 0-1-1H5a1 1 0 0 0-1 1v4.5zm-5.5 1V15a1 1 0 0 0 1 1h4.5v-5.5zm6.5 5.5H15a1 1 0 0 0 1-1v-3.5a1 1 0 0 0-1-1h-4.5z");
}

</style>
