<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8uvlibxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-start-arrow-notch-outline" /></template>
<style>
.y8uvlibxn {
  fill: currentColor;
  d: path("M13 19L2 12l11-7l-3.425 6H22v2H9.575z");
}

</style>
