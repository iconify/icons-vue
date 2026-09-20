<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="liborwxsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-right-up-20-filled" /></template>
<style>
.liborwxsw {
  fill: currentColor;
  d: path("M16.78 9.28a.75.75 0 0 0 0-1.06l-4-4a.75.75 0 0 0-1.06 0l-4 4a.75.75 0 0 0 1.06 1.06l2.72-2.72V13a1.5 1.5 0 0 1-1.5 1.5H3.75a.75.75 0 0 0 0 1.5H10a3 3 0 0 0 3-3V6.56l2.72 2.72a.75.75 0 0 0 1.06 0");
}

</style>
