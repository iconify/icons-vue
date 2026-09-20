<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p454zibvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-start-diamond" /></template>
<style>
.p454zibvy {
  fill: currentColor;
  d: path("m9 19l-7-7l7-7l6 6h7v2h-7z");
}

</style>
