<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0j19b4km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:android-cell-4-bar-outline" /></template>
<style>
.t0j19b4km {
  fill: currentColor;
  d: path("M1.5 20v-8h3v8zm6 0V9.5h3V20zm6 0V7h3v13zm6 0V4h3v16z");
}

</style>
