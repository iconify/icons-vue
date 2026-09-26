<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nw9u85b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-20-regular" /></template>
<style>
.nw9u85b5f {
  fill: currentColor;
  d: path("M12.64 1.02a.5.5 0 0 1 .34.62l-5 17a.5.5 0 0 1-.96-.28l5-17a.5.5 0 0 1 .62-.34M5.127 5.169a.5.5 0 0 1 .748.664L2.169 10l3.705 4.168a.5.5 0 0 1-.748.664l-4-4.5a.5.5 0 0 1 0-.664zm9.042-.042a.5.5 0 0 1 .706.042l4 4.5a.5.5 0 0 1 0 .664l-4 4.5a.5.5 0 0 1-.748-.664L17.831 10l-3.705-4.168a.5.5 0 0 1 .042-.706");
}

</style>
