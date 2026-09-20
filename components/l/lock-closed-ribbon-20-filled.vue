<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lql7q7uto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-closed-ribbon-20-filled" /></template>
<style>
.lql7q7uto {
  fill: currentColor;
  d: path("M17 18.5a.5.5 0 0 1-.8.4L15 18l-1.2.9a.5.5 0 0 1-.8-.4v-2.035A4 4 0 0 0 15 17a4 4 0 0 0 2-.535zM10 1a4 4 0 0 1 4 4v2.05a2.5 2.5 0 0 1 1.969 2.068A4 4 0 0 0 12 15.645V18H6.5A2.5 2.5 0 0 1 4 15.5v-6a2.5 2.5 0 0 1 2-2.45V5a4 4 0 0 1 4-4m5 9a3 3 0 1 1 0 6a3 3 0 0 1 0-6m-5 1.5a1 1 0 1 0 0 2a1 1 0 0 0 0-2M10 2a3 3 0 0 0-3 3v2h6V5a3 3 0 0 0-3-3");
}

</style>
