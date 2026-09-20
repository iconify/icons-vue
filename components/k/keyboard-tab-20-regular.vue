<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="foy2emhmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-tab-20-regular" /></template>
<style>
.foy2emhmj {
  fill: currentColor;
  d: path("M9.354 4.146a.5.5 0 1 0-.708.708L13.293 9.5H3.5a.5.5 0 0 0 0 1h9.793l-4.647 4.646a.5.5 0 0 0 .708.708l5.5-5.5a.5.5 0 0 0 0-.708zM17 4.5a.5.5 0 0 0-1 0v11a.5.5 0 0 0 1 0z");
}

</style>
