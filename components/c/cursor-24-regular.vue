<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym0jfxtnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cursor-24-regular" /></template>
<style>
.ym0jfxtnd {
  fill: currentColor;
  d: path("M5.5 3.483c0-1.248 1.436-1.95 2.421-1.184l13.514 10.513c1.128.877.508 2.684-.92 2.684h-6.853c-.505 0-.981.23-1.294.626l-4.191 5.3c-.882 1.116-2.677.492-2.677-.93zm15.014 10.513L7 3.483v17.009l4.191-5.3a3.15 3.15 0 0 1 2.47-1.196z");
}

</style>
