<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="elfw_d1mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-right-20-filled" /></template>
<style>
.elfw_d1mk {
  fill: currentColor;
  d: path("M10.72 3.22a.75.75 0 0 1 1.06 0l4 4a.75.75 0 0 1 0 1.06l-4 4a.75.75 0 1 1-1.06-1.06l2.72-2.72H7A1.5 1.5 0 0 0 5.5 10v6.25a.75.75 0 0 1-1.5 0V10a3 3 0 0 1 3-3h6.44l-2.72-2.72a.75.75 0 0 1 0-1.06");
}

</style>
