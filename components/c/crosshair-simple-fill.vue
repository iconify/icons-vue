<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ky4sdd37g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:crosshair-simple-fill" /></template>
<style>
.ky4sdd37g {
  fill: currentColor;
  d: path("M176 136h23.54A72.11 72.11 0 0 1 136 199.54V176a8 8 0 0 0-16 0v23.54A72.11 72.11 0 0 1 56.46 136H80a8 8 0 0 0 0-16H56.46A72.11 72.11 0 0 1 120 56.46V80a8 8 0 0 0 16 0V56.46A72.11 72.11 0 0 1 199.54 120H176a8 8 0 0 0 0 16m56-8A104 104 0 1 1 128 24a104.11 104.11 0 0 1 104 104m-16 0a88 88 0 1 0-88 88a88.1 88.1 0 0 0 88-88");
}

</style>
