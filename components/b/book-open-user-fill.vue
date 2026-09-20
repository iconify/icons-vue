<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b6053ib_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:book-open-user-fill" /></template>
<style>
.b6053ib_z {
  fill: currentColor;
  d: path("M240 80v120a8 8 0 0 1-8 8h-72a24 24 0 0 0-24 23.94a7.9 7.9 0 0 1-5.12 7.55A8 8 0 0 1 120 232a24 24 0 0 0-24-24H24a8 8 0 0 1-8-8V80a8 8 0 0 1 8-8h64a32 32 0 0 1 32 32v63.73a8.17 8.17 0 0 0 7.47 8.25a8 8 0 0 0 8.53-8V104a32 32 0 0 1 32-32h64a8 8 0 0 1 8 8M88.81 56H89a47.92 47.92 0 0 1 36 17.4a4 4 0 0 0 6.08 0A47.92 47.92 0 0 1 167 56h.19a4 4 0 0 0 3.54-5.84a48 48 0 0 0-85.46 0A4 4 0 0 0 88.81 56");
}

</style>
