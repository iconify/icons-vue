<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l39soabmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-distribute-top-16-filled" /></template>
<style>
.l39soabmh {
  fill: currentColor;
  d: path("M1.5 1a.5.5 0 0 0 0 1h13a.5.5 0 0 0 0-1zm0 7a.5.5 0 0 0 0 1h13a.5.5 0 0 0 0-1zm8 6a1.5 1.5 0 0 0 1.5-1.5v-1A1.5 1.5 0 0 0 9.5 10h-3A1.5 1.5 0 0 0 5 11.5v1A1.5 1.5 0 0 0 6.5 14zm2-7A1.5 1.5 0 0 0 13 5.5v-1A1.5 1.5 0 0 0 11.5 3h-7A1.5 1.5 0 0 0 3 4.5v1A1.5 1.5 0 0 0 4.5 7z");
}

</style>
