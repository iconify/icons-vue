<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j4ghm3bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-48-regular" /></template>
<style>
.j4ghm3bvf {
  fill: currentColor;
  d: path("M24 5.25c.69 0 1.25.56 1.25 1.25v16.25H41.5a1.25 1.25 0 1 1 0 2.5H25.25V41.5a1.25 1.25 0 1 1-2.5 0V25.25H6.5a1.25 1.25 0 1 1 0-2.5h16.25V6.5c0-.69.56-1.25 1.25-1.25");
}

</style>
