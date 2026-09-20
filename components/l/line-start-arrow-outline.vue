<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdwwobb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-start-arrow-outline" /></template>
<style>
.hdwwobb6o {
  fill: currentColor;
  d: path("M11.808 16.827L4.212 12l7.596-4.827V11.5h9.115v1h-9.115zm-1-1.823V8.996L6.09 12zm0-3.004");
}

</style>
