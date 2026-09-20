<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wmjgx4_sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-off-32-regular" /></template>
<style>
.wmjgx4_sy {
  fill: currentColor;
  d: path("M2.293 2.293a1 1 0 0 1 1.414 0l26 26a1 1 0 1 1-1.414 1.414l-3.127-3.127A13.94 13.94 0 0 1 16 30C8.268 30 2 23.732 2 16c0-3.506 1.288-6.712 3.418-9.168L2.293 3.707a1 1 0 0 1 0-1.414m4.545 5.959A11.95 11.95 0 0 0 4 16c0 6.627 5.373 12 12 12c2.954 0 5.656-1.07 7.746-2.84zM16 2c7.732 0 14 6.268 14 14c0 2.962-.921 5.71-2.491 7.972l-1.444-1.444A11.94 11.94 0 0 0 28 16c0-6.627-5.373-12-12-12c-2.409 0-4.65.712-6.53 1.934L8.027 4.49A13.94 13.94 0 0 1 16 2");
}

</style>
