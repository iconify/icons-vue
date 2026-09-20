<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zozjmacgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:location-arrow-32-filled" /></template>
<style>
.zozjmacgs {
  fill: currentColor;
  d: path("M26.278 3.138c1.617-.622 3.206.967 2.584 2.585l-8.46 21.994c-.696 1.812-3.306 1.668-3.8-.209l-2.375-9.023a1 1 0 0 0-.712-.712l-9.023-2.375c-1.877-.494-2.02-3.104-.209-3.8z");
}

</style>
