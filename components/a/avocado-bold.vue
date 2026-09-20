<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kz-vt5b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:avocado-bold" /></template>
<style>
.kz-vt5b7o {
  fill: currentColor;
  d: path("M128 108a52 52 0 1 0 52 52a52.06 52.06 0 0 0-52-52m0 80a28 28 0 1 1 28-28a28 28 0 0 1-28 28m86.76-58.68L185 45.17A60 60 0 0 0 71.42 44l-29.5 83.46a92 92 0 1 0 172.84 1.86M128 228a68.05 68.05 0 0 1-63.59-92.15c0-.09.07-.18.1-.26L94.05 52a36 36 0 0 1 68.17.78l.09.27l29.82 84.28A68 68 0 0 1 128 228");
}

</style>
