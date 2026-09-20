<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yhj_eqnyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:important-12-regular" /></template>
<style>
.yhj_eqnyu {
  fill: currentColor;
  d: path("M4.283 2.98a1.735 1.735 0 1 1 3.434 0l-.576 4.03a1.153 1.153 0 0 1-2.282 0zm2.444-.142a.735.735 0 1 0-1.454 0l.576 4.03a.153.153 0 0 0 .303 0zM6 11a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
