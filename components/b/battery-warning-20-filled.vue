<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rweiam1uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-warning-20-filled" /></template>
<style>
.rweiam1uq {
  fill: currentColor;
  d: path("M3.604 9.554a1 1 0 0 1 1.79-.001l3.5 6.999A1 1 0 0 1 7.998 18H1.003a1 1 0 0 1-.896-1.448zm.894 6.445a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1M16 5a3 3 0 0 1 3 3a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1l-.004.154A3 3 0 0 1 16 15H9.238L6.292 9.106c-.738-1.475-2.843-1.474-3.58.001L.467 13.603A3 3 0 0 1 0 12V8a3 3 0 0 1 3-3zM4.498 10.995a.5.5 0 0 0-.5.5v3.002a.5.5 0 1 0 1.001 0v-3.002a.5.5 0 0 0-.5-.5");
}

</style>
