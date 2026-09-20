<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_ix09bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:live-off-24-filled" /></template>
<style>
.b_ix09bkp {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-8.334-8.334a1.5 1.5 0 0 1-.388.054a1.5 1.5 0 0 1-1.447-1.889l-1.86-1.86a4 4 0 0 0 .48 5.077a1 1 0 0 1-1.414 1.414A6 6 0 0 1 7.26 8.32L5.837 6.897a8 8 0 0 0 .506 10.76a1.001 1.001 0 0 1-1.414 1.414c-3.727-3.727-3.896-9.663-.51-13.592l-2.2-2.199a.75.75 0 0 1 0-1.06m15.436 2.709a1 1 0 0 1 1.414 0c3.358 3.358 3.825 8.508 1.409 12.369l-1.461-1.461a8 8 0 0 0-1.362-9.494a1 1 0 0 1 0-1.414m-2.829 2.828a1 1 0 0 1 1.414 0a6 6 0 0 1 1.282 6.585l-1.595-1.595a4 4 0 0 0-1.1-3.576a1 1 0 0 1 0-1.414");
}

</style>
