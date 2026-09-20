<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7-_t9i2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-upload-24-filled" /></template>
<style>
.k7-_t9i2i {
  fill: currentColor;
  d: path("M5.5 2a1 1 0 0 0 0 2h13a1 1 0 1 0 0-2zm7.207 3.793a1 1 0 0 0-1.414 0l-5 5a1 1 0 1 0 1.414 1.414L11 8.914V21a1 1 0 1 0 2 0V8.914l3.293 3.293a1 1 0 0 0 1.414-1.414z");
}

</style>
