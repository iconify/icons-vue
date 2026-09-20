<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r9n3sj6ek"/><path class="oorslor6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-openhab" /></template>
<style>
.oorslor6b {
  fill: var(--svg-color--474747, #474747);
  d: path("M16 2A14 14 0 1 1 5.431 25.162l.495-.5l.359-.359l.36-.36l.36-.36l.015-.015a11.708 11.708 0 1 0-2.5-5.03l-.78.782l-1.04 1.045A13.994 13.994 0 0 1 16 2");
}

.r9n3sj6ek {
  fill: var(--svg-color--e64a19, #e64a19);
  d: path("M3.449 21.989L14.4 11.025l1.6-1.6l1.6 1.6l8.087 8.087l-.012.041l-.16.47l-.181.459l-.2.448l-.224.437l-.2.354L16 12.62L4.613 24.016a13 13 0 0 1-1.164-2.028Z");
}

</style>
