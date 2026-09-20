<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zav8sacea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:luggage-20-filled" /></template>
<style>
.zav8sacea {
  fill: currentColor;
  d: path("M6.5 2a.5.5 0 0 0 0 1H7v1h-.5A2.5 2.5 0 0 0 4 6.5v8a2.5 2.5 0 0 0 2 2.45v.55a.5.5 0 0 0 1 0V17h6v.5a.5.5 0 0 0 1 0v-.55a2.5 2.5 0 0 0 2-2.45v-8A2.5 2.5 0 0 0 13.5 4H13V3h.5a.5.5 0 0 0 0-1zM12 3v1H8V3zM6.5 8.5A.5.5 0 0 1 7 8h6a.5.5 0 0 1 0 1H7a.5.5 0 0 1-.5-.5");
}

</style>
