<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hxbgffb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:down-arrow" /></template>
<style>
.hxbgffb0y {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M64 105.05L32.86 62.58h19.42V22.95h23.23v39.63h19.62z");
}

</style>
