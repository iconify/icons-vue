<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yiavoac0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-left-right-48-filled" /></template>
<style>
.yiavoac0w {
  fill: currentColor;
  d: path("M40.057 9.894a1.5 1.5 0 0 0-1.113-2.787L7.392 19.702c-2.078.83-2.104 3.76-.042 4.627l29.258 12.293l-7.728 3.513a1.5 1.5 0 0 0 1.241 2.73l11-5a1.5 1.5 0 0 0 .764-1.942l-5-12a1.5 1.5 0 1 0-2.77 1.154l3.66 8.781L9.637 22.036z");
}

</style>
