<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f6-v9efio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-5-20-filled" /></template>
<style>
.f6-v9efio {
  fill: currentColor;
  d: path("M16 5a3 3 0 0 1 3 3a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1l-.004.154A3 3 0 0 1 16 15H3a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3zM3 7a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h5.5a1 1 0 0 0 1-1V8a1 1 0 0 0-1-1z");
}

</style>
