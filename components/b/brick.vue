<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymmezihid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:brick" /></template>
<style>
.ymmezihid {
  fill: currentColor;
  d: path("M3 19V8.712h2.827V5h4.789v3.712h2.769V5h4.788v3.712H21V19z");
}

</style>
