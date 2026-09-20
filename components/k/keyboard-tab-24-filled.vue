<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxhq2o3am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-tab-24-filled" /></template>
<style>
.jxhq2o3am {
  fill: currentColor;
  d: path("m18.207 11.293l-6.5-6.5a1 1 0 0 0-1.497 1.32l.083.094L15.086 11H4a1 1 0 0 0-.993.883L3 12a1 1 0 0 0 .883.993L4 13h11.086l-4.793 4.793a1 1 0 0 0-.083 1.32l.083.094a1 1 0 0 0 1.32.083l.094-.083l6.5-6.5a1 1 0 0 0 .083-1.32zl-6.5-6.5zM21 18.5v-13a1 1 0 1 0-2 0v13a1 1 0 1 0 2 0");
}

</style>
