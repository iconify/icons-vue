<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guu5dobtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:login-sharp" /></template>
<style>
.guu5dobtf {
  fill: currentColor;
  d: path("M11.98 20v-1H19V5h-7.02V4H20v16zm-.71-4.461l-.703-.72l2.32-2.319H4.019v-1h8.868l-2.32-2.32l.702-.718L14.808 12z");
}

</style>
