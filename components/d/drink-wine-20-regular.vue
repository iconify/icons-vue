<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m8wvbpboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:drink-wine-20-regular" /></template>
<style>
.m8wvbpboy {
  fill: currentColor;
  d: path("M13.452 8.075a.5.5 0 0 0-.986-.164a2.5 2.5 0 0 1-2.048 2.054a.5.5 0 0 0 .167.986a3.5 3.5 0 0 0 2.867-2.876M5.5 2a.5.5 0 0 0-.5.5V8a5 5 0 0 0 4.5 4.975V17h-2a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1h-2v-4.025A5 5 0 0 0 15 8V2.5a.5.5 0 0 0-.5-.5zM6 5.5V3h8v2.5zm0 1h8V8a4 4 0 0 1-8 0z");
}

</style>
