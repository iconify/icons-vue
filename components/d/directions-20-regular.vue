<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tmfy1kclr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:directions-20-regular" /></template>
<style>
.tmfy1kclr {
  fill: currentColor;
  d: path("M7.878 1.878a3 3 0 0 1 4.243 0l5.998 6a3 3 0 0 1 0 4.242l-5.998 5.999a3 3 0 0 1-4.243 0l-6-6a3 3 0 0 1 0-4.242zm3.535.707a2 2 0 0 0-2.828 0l-5.998 6a2 2 0 0 0 0 2.827l5.998 6a2 2 0 0 0 2.828 0l5.999-6a2 2 0 0 0 0-2.828zm-.767 2.562a.5.5 0 0 1 .707 0l2 2a.5.5 0 0 1 0 .707l-2 2a.5.5 0 0 1-.707-.707L11.793 8H10a2 2 0 0 0-2 2v3a.5.5 0 0 1-1 0v-3a3 3 0 0 1 3-3h1.793l-1.147-1.146a.5.5 0 0 1 0-.707");
}

</style>
