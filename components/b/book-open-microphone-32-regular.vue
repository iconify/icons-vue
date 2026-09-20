<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x1ap9zzze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-microphone-32-regular" /></template>
<style>
.x1ap9zzze {
  fill: currentColor;
  d: path("M29.5 21a1 1 0 0 1 1 1a6.5 6.5 0 0 1-5.5 6.423V29.5a1 1 0 1 1-2 0v-1.077A6.5 6.5 0 0 1 17.5 22a1 1 0 1 1 2 0a4.5 4.5 0 1 0 9 0a1 1 0 0 1 1-1m-17-17c1.414 0 2.675.652 3.5 1.67A4.5 4.5 0 0 1 19.5 4H28a2 2 0 0 1 2 2v13.55a2.5 2.5 0 0 0-1.5.159V18.5a4.5 4.5 0 0 0-.5-2.061V6h-8.5A2.5 2.5 0 0 0 17 8.5v11.503c-.606.456-1 1.18-1 1.997a7.97 7.97 0 0 0 2.612 5.91A4.5 4.5 0 0 1 16 26.33A4.5 4.5 0 0 1 12.5 28H4a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2zM4 26h8.5a2.5 2.5 0 0 0 2.5-2.5v-15A2.5 2.5 0 0 0 12.5 6H4zm20-10.5a3 3 0 0 1 3 3V22a3 3 0 1 1-6 0v-3.5a3 3 0 0 1 3-3");
}

</style>
