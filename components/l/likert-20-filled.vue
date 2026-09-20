<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="opvrbdezm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:likert-20-filled" /></template>
<style>
.opvrbdezm {
  fill: currentColor;
  d: path("M6 16v-5.5H2V13a3 3 0 0 0 3 3zm1 0h8a3 3 0 0 0 3-3v-2.5H7zm2-2a.75.75 0 1 1 0-1.5a.75.75 0 0 1 0 1.5m2.25 0a.75.75 0 1 1 0-1.5a.75.75 0 0 1 0 1.5m2.25 0a.75.75 0 1 1 0-1.5a.75.75 0 0 1 0 1.5m2.25 0a.75.75 0 1 1 0-1.5a.75.75 0 0 1 0 1.5M18 9.5V7a3 3 0 0 0-3-3H7v5.5zM9.75 6.75a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m2.25 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m2.25 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m2.25 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0M6 4H5a3 3 0 0 0-3 3v2.5h4z");
}

</style>
