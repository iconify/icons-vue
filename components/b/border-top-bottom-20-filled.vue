<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h7vizdbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:border-top-bottom-20-filled" /></template>
<style>
.h7vizdbee {
  fill: currentColor;
  d: path("M6 4.502a1.5 1.5 0 0 0-1.396.949a.75.75 0 1 1-1.413-.492h-.005A3 3 0 0 1 6 3.002h8c1.29 0 2.39.814 2.814 1.957h-.003a.75.75 0 0 1-1.381.586l-.004-.01l-.024-.067A1.5 1.5 0 0 0 14 4.502zM3 11.25a.75.75 0 0 0 1.5 0v-2.5a.75.75 0 0 0-1.5 0zm12.5 0a.75.75 0 0 0 1.5 0v-2.5a.75.75 0 0 0-1.5 0zM4.604 14.553A1.5 1.5 0 0 0 6 15.502h8a1.5 1.5 0 0 0 1.426-1.033l.003-.01a.75.75 0 0 1 1.382.586h.003A3 3 0 0 1 14 17.002H6c-1.29 0-2.39-.814-2.814-1.957h.005a.75.75 0 1 1 1.413-.492");
}

</style>
