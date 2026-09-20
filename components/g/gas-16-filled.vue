<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lp9x14b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gas-16-filled" /></template>
<style>
.lp9x14b9z {
  fill: currentColor;
  d: path("M11.5 1a.5.5 0 0 1 .5.5v2.77c.597.345 1 .99 1 1.73v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h1a1 1 0 0 0-1-1H3.5a.5.5 0 0 1 0-1H5a2 2 0 0 1 2 2h.732l1.852-2.777l.038-.05A.5.5 0 0 1 10 1zm-1.146 5.646a.5.5 0 0 0-.708 0L8 8.293L6.354 6.646a.5.5 0 1 0-.708.708L7.293 9l-1.647 1.646a.5.5 0 1 0 .708.707L8 9.708l1.646 1.646a.5.5 0 1 0 .707-.707L8.708 9l1.646-1.646a.5.5 0 0 0 0-.708M8.934 4H11V2h-.732z");
}

</style>
