<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztdk8i0xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:equalizer" /></template>
<style>
.ztdk8i0xj {
  fill: currentColor;
  d: path("M5 19v-5.808h3V19zm5.5 0V5h3v14zm5.5 0V9.808h3V19z");
}

</style>
