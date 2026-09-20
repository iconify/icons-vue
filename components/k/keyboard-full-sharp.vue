<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4f2ows3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-full-sharp" /></template>
<style>
.r4f2ows3v {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-5h16V6H4z");
}

</style>
