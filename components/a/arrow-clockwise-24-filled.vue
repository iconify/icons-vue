<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxx0t3lxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-clockwise-24-filled" /></template>
<style>
.mxx0t3lxd {
  fill: currentColor;
  d: path("M5 12a7 7 0 0 1 10.608-6H15a1 1 0 1 0 0 2h3a1 1 0 0 0 1-1V4a1 1 0 1 0-2 0v.516a9 9 0 1 0 3.93 6.36a1 1 0 1 0-1.984.248q.053.43.054.876a7 7 0 1 1-14 0");
}

</style>
