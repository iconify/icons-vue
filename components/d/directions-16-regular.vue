<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ut--vjbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:directions-16-regular" /></template>
<style>
.ut--vjbgm {
  fill: currentColor;
  d: path("M6.232 1.232a2.5 2.5 0 0 1 3.536 0l4.999 5c.976.976.976 2.56 0 3.536l-5 4.999a2.5 2.5 0 0 1-3.535 0l-5-5a2.5 2.5 0 0 1 0-3.536zm2.829.707a1.5 1.5 0 0 0-2.122 0l-5 5a1.5 1.5 0 0 0 0 2.122l5 4.999a1.5 1.5 0 0 0 2.122 0l4.999-5a1.5 1.5 0 0 0 0-2.121zm-.414 2.707a.5.5 0 0 1 .707 0l1.5 1.5a.5.5 0 0 1 0 .708l-1.5 1.5a.5.5 0 0 1-.707-.707L9.293 7H8.5A1.5 1.5 0 0 0 7 8.5v2a.5.5 0 0 1-1 0v-2A2.5 2.5 0 0 1 8.5 6h.793l-.646-.646a.5.5 0 0 1 0-.708");
}

</style>
