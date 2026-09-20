<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vxq6bdcxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-bar-horizontal-descending-16-filled" /></template>
<style>
.vxq6bdcxu {
  fill: currentColor;
  d: path("M13 5a2 2 0 1 0 0-4H3a2 2 0 1 0 0 4zM7 15a2 2 0 1 0 0-4H3a2 2 0 1 0 0 4zm4-7a2 2 0 0 1-2 2H3a2 2 0 1 1 0-4h6a2 2 0 0 1 2 2");
}

</style>
