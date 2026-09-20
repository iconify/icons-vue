<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x2_l8ebxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sort-up-lines-16-regular" /></template>
<style>
.x2_l8ebxm {
  fill: currentColor;
  d: path("M13 14.5a.5.5 0 0 1-1 0V2.707l-1.146 1.147a.5.5 0 0 1-.708-.708l2-2a.5.5 0 0 1 .708 0l2 2a.5.5 0 0 1-.708.708L13 2.707zM2.5 13a.5.5 0 0 1 0-1h7a.5.5 0 0 1 0 1zm2-3a.5.5 0 0 1 0-1h5a.5.5 0 0 1 0 1zM6 6.5a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 0-1h-3a.5.5 0 0 0-.5.5");
}

</style>
