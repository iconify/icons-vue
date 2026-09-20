<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vhgelnb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-three-focus-center-16-filled" /></template>
<style>
.vhgelnb6v {
  fill: currentColor;
  d: path("M2 11.5A2.5 2.5 0 0 0 4.5 14h7a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 11.5 2h-7A2.5 2.5 0 0 0 2 4.5zM4.5 13A1.5 1.5 0 0 1 3 11.5V10h10v1.5a1.5 1.5 0 0 1-1.5 1.5zM13 6H3V4.5A1.5 1.5 0 0 1 4.5 3h7A1.5 1.5 0 0 1 13 4.5z");
}

</style>
