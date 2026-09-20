<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucy1exbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airlines-outline" /></template>
<style>
.ucy1exbel {
  fill: currentColor;
  d: path("M4.954 18h12.435l2.403-12h-5.967zM3 19L13.289 5h7.73l-2.807 14zm11.289-5.616q.799 0 1.351-.544t.552-1.333t-.552-1.34t-1.351-.552q-.784 0-1.325.549t-.541 1.342t.541 1.336t1.325.542M4.954 18h12.435z");
}

</style>
