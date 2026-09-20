<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmfk_ccen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-start-diamond-outline-sharp" /></template>
<style>
.jmfk_ccen {
  fill: currentColor;
  d: path("M9 16.175L13.175 12L9 7.825L4.825 12zM9 19l-7-7l7-7l6 6h7v2h-7zm0-7");
}

</style>
