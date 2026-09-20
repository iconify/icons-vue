<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ploi8_bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:gitlab-logo-simple-thin" /></template>
<style>
.ploi8_bxm {
  fill: currentColor;
  d: path("M226.27 118.11L206.38 42a7.94 7.94 0 0 0-15.16-.75L172.57 92H83.43L64.78 41.24a7.94 7.94 0 0 0-15.16.76l-19.89 76.11a53.16 53.16 0 0 0 20.44 56.68l73.27 51.76a7.9 7.9 0 0 0 9.12 0l73.27-51.76a53.16 53.16 0 0 0 20.44-56.68m-25.05 50.14L128 220l-73.22-51.75a45.11 45.11 0 0 1-17.31-48.11l19.84-76l19.58 53.24a4 4 0 0 0 3.75 2.62h94.72a4 4 0 0 0 3.75-2.62l19.57-53.22l19.85 76a45.11 45.11 0 0 1-17.31 48.09");
}

</style>
