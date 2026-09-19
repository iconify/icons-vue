<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5804ubjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-eject" /></template>
<style>
.w5804ubjm {
  fill: currentColor;
  d: path("M5 17h14v2H5zm7-12L5.33 15h13.34z");
}

</style>
