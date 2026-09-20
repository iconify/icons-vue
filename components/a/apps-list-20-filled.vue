<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hq4r7sm2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:apps-list-20-filled" /></template>
<style>
.hq4r7sm2z {
  fill: currentColor;
  d: path("M8 4.5a.5.5 0 0 1 .5-.5h9a.5.5 0 0 1 0 1h-9a.5.5 0 0 1-.5-.5m0 6a.5.5 0 0 1 .5-.5h9a.5.5 0 0 1 0 1h-9a.5.5 0 0 1-.5-.5m0 6a.5.5 0 0 1 .5-.5h9a.5.5 0 0 1 0 1h-9a.5.5 0 0 1-.5-.5m-6-1A1.5 1.5 0 0 1 3.5 14h1A1.5 1.5 0 0 1 6 15.5v1A1.5 1.5 0 0 1 4.5 18h-1A1.5 1.5 0 0 1 2 16.5zm0-6A1.5 1.5 0 0 1 3.5 8h1A1.5 1.5 0 0 1 6 9.5v1A1.5 1.5 0 0 1 4.5 12h-1A1.5 1.5 0 0 1 2 10.5zm0-6A1.5 1.5 0 0 1 3.5 2h1A1.5 1.5 0 0 1 6 3.5v1A1.5 1.5 0 0 1 4.5 6h-1A1.5 1.5 0 0 1 2 4.5z");
}

</style>
