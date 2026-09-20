<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o6vuhab2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-up-down-16-regular" /></template>
<style>
.o6vuhab2d {
  fill: currentColor;
  d: path("M4.146 6.354a.5.5 0 0 0 .708 0L8 3.207l3.146 3.147a.5.5 0 0 0 .708-.708l-3.5-3.5a.5.5 0 0 0-.708 0l-3.5 3.5a.5.5 0 0 0 0 .708m0 3.292a.5.5 0 0 1 .708 0L8 12.793l3.146-3.147a.5.5 0 0 1 .708.708l-3.5 3.5a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 0 1 0-.708");
}

</style>
