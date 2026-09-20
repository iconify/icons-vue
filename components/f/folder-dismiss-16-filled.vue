<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gp1y3r_1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-dismiss-16-filled" /></template>
<style>
.gp1y3r_1w {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m1-3A2.5 2.5 0 0 1 15 6.5v.757A5.5 5.5 0 0 0 6.602 14H3.5A2.5 2.5 0 0 1 1 11.5V7h4.586a1.5 1.5 0 0 0 1.06-.44L9.207 4zm.854 5.646a.5.5 0 0 0-.707 0L11.5 10.793l-1.146-1.147a.5.5 0 1 0-.708.707l1.147 1.147l-1.147 1.146a.5.5 0 1 0 .707.707l1.147-1.146l1.146 1.146a.5.5 0 1 0 .707-.707L12.208 11.5l1.146-1.146a.5.5 0 0 0 0-.708M5.586 2a1.5 1.5 0 0 1 1.06.44L8 3.792l-2.06 2.06A.5.5 0 0 1 5.585 6H1V4.5A2.5 2.5 0 0 1 3.5 2z");
}

</style>
