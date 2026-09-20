<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a3mpkvpjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-bidirectional-down-right-20-filled" /></template>
<style>
.a3mpkvpjo {
  fill: currentColor;
  d: path("M13.78 2.22a.75.75 0 1 0-1.06 1.06L15.44 6H9a3 3 0 0 0-3 3v6.44l-2.72-2.72a.75.75 0 0 0-1.06 1.06l4 4a.75.75 0 0 0 1.06 0l4-4a.75.75 0 1 0-1.06-1.06L7.5 15.44V9A1.5 1.5 0 0 1 9 7.5h6.44l-2.72 2.72a.75.75 0 1 0 1.06 1.06l4-4a.75.75 0 0 0 0-1.06z");
}

</style>
