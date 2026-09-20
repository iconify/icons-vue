<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t-ihjpbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:directions-16-filled" /></template>
<style>
.t-ihjpbxh {
  fill: currentColor;
  d: path("M6.232 1.232a2.5 2.5 0 0 1 3.536 0l4.999 5a2.5 2.5 0 0 1 0 3.535l-5 5a2.5 2.5 0 0 1-3.535 0l-5-5a2.5 2.5 0 0 1 0-3.535zm3.122 3.415a.5.5 0 0 0-.707.707L9.293 6H8.5A2.5 2.5 0 0 0 6 8.5v2a.5.5 0 0 0 1 0v-2A1.5 1.5 0 0 1 8.5 7h.793l-.646.647a.5.5 0 1 0 .707.707l1.5-1.5a.5.5 0 0 0 0-.707z");
}

</style>
