<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="j5p8hzb2e"/><path class="p902t1bln"/><path class="ti19ytvcr"/><path class="kjtw8iufa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-kuwait" /></template>
<style>
.j5p8hzb2e {
  fill: var(--svg-color--007a3d, #007a3d);
  d: path("M32 5H4a4 4 0 0 0-4 4v4.5h36V9a4 4 0 0 0-4-4");
}

.kjtw8iufa {
  fill: var(--svg-color--141414, #141414);
  d: path("M1.205 6.138A4 4 0 0 0 0 9v18c0 1.122.462 2.135 1.205 2.862L9 22.5v-9z");
}

.p902t1bln {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-4.5H0z");
}

.ti19ytvcr {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 13.5h36v9H0z");
}

</style>
