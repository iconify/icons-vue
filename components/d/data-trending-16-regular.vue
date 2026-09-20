<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jt4vi7owq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-trending-16-regular" /></template>
<style>
.jt4vi7owq {
  fill: currentColor;
  d: path("M3 2.5a.5.5 0 0 0-1 0v9A2.5 2.5 0 0 0 4.5 14h9a.5.5 0 0 0 0-1h-9A1.5 1.5 0 0 1 3 11.5zm7 2a.5.5 0 0 0 .5.5h1.793L9 8.293L7.354 6.646a.5.5 0 0 0-.708 0l-2.5 2.5a.5.5 0 1 0 .708.708L7 7.707l1.646 1.647a.5.5 0 0 0 .708 0L13 5.707v1.87a.5.5 0 0 0 1 0V4.5a.5.5 0 0 0-.5-.5h-3a.5.5 0 0 0-.5.5");
}

</style>
