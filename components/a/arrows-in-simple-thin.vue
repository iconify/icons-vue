<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="t67m_jb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-in-simple-thin" /></template>
<style>
.t67m_jb2b {
  fill: currentColor;
  d: path("M210.83 50.83L153.66 108H192a4 4 0 0 1 0 8h-48a4 4 0 0 1-4-4V64a4 4 0 0 1 8 0v38.34l57.17-57.17a4 4 0 1 1 5.66 5.66M112 140H64a4 4 0 0 0 0 8h38.34l-57.17 57.17a4 4 0 0 0 5.66 5.66L108 153.66V192a4 4 0 0 0 8 0v-48a4 4 0 0 0-4-4");
}

</style>
