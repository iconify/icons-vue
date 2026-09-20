<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c_1q3gb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:channel-20-filled" /></template>
<style>
.c_1q3gb1o {
  fill: currentColor;
  d: path("M5.5 3a2.5 2.5 0 0 0-2.302 1.523Q3.347 4.5 3.5 4.5A2 2 0 1 1 3 8.437V14.5A2.5 2.5 0 0 0 5.5 17h9a2.5 2.5 0 0 0 2.5-2.5v-9A2.5 2.5 0 0 0 14.5 3zM7 8.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5m.5 2.5h3a.5.5 0 0 1 0 1h-3a.5.5 0 0 1 0-1m-4-5.5a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
