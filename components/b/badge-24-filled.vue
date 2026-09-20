<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk5orfbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:badge-24-filled" /></template>
<style>
.yk5orfbbo {
  fill: currentColor;
  d: path("M16 4.502a3.5 3.5 0 0 0 5.001 3.163L21 18.25A2.75 2.75 0 0 1 18.25 21H5.75A2.75 2.75 0 0 1 3 18.25V5.75A2.75 2.75 0 0 1 5.75 3h10.588A3.5 3.5 0 0 0 16 4.502m3.5-2.5a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5");
}

</style>
