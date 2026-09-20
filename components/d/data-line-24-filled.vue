<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjubtgbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-line-24-filled" /></template>
<style>
.hjubtgbrv {
  fill: currentColor;
  d: path("M16 6a3 3 0 1 1 2.524 2.962l-2.038 3.358a3 3 0 0 1-4.749 3.65l-3.741 1.87Q8 17.92 8 18a3 3 0 1 1-.465-1.606l3.531-1.765a3 3 0 0 1 4.275-3.313l1.798-2.963A3 3 0 0 1 16 6");
}

</style>
