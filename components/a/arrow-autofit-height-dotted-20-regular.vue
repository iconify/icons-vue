<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o1lqldbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-autofit-height-dotted-20-regular" /></template>
<style>
.o1lqldbck {
  fill: currentColor;
  d: path("M16.142 4.81L14.5 3.11l-1.641 1.7a.5.5 0 0 1-.72-.695l1.821-1.886a.75.75 0 0 1 1.08 0l1.82 1.886a.5.5 0 1 1-.72.694M5 3a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h4.5a.5.5 0 0 0 0-1H5a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h4.5a.5.5 0 0 0 0-1zm9.503 2a.5.5 0 0 1 .5.5V7a.5.5 0 1 1-1 0V5.5a.5.5 0 0 1 .5-.5m.5 8a.5.5 0 1 0-1 0v1.5a.5.5 0 0 0 1 0zm-.5-4a.5.5 0 0 1 .5.5v1a.5.5 0 1 1-1 0v-1a.5.5 0 0 1 .5-.5m1.639 6.19l-1.641 1.7l-1.641-1.7a.5.5 0 1 0-.72.695l1.821 1.886a.75.75 0 0 0 1.08 0l1.82-1.886a.5.5 0 1 0-.72-.694");
}

</style>
