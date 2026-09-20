<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zzdh3tbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-20-regular" /></template>
<style>
.zzdh3tbjx {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V8h7v7.5a.5.5 0 0 0 1 0V6a2 2 0 0 0-2-2zM3 8h6v6a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1zm0-1V6a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v1zm2 2.5a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1z");
}

</style>
