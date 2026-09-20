<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r6f9x3wzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-add-above-20-filled" /></template>
<style>
.r6f9x3wzd {
  fill: currentColor;
  d: path("M16.5 8a.5.5 0 0 1 .5.5V14a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V8.5a.5.5 0 0 1 .5-.5zm0-5a.5.5 0 0 1 0 1h-13a.5.5 0 0 1 0-1z");
}

</style>
