<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccl2_x_bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:2d-sharp" /></template>
<style>
.ccl2_x_bz {
  fill: currentColor;
  d: path("M6.885 14.692h3.884v-.884h-3v-1.423h3V9.308H6.885v.884h3v1.424h-3zM4 20V4h16v16zm8.846-5.308h3.789l.596-.615V9.904l-.597-.596h-3.788zm.885-.884v-3.616h2.615v3.616z");
}

</style>
