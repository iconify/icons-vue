<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v74f8fbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-badge-48-filled" /></template>
<style>
.v74f8fbmj {
  fill: currentColor;
  d: path("M34.675 6A7 7 0 0 0 44 15.325V28.75A7.25 7.25 0 0 1 36.75 36H26.397l-10.85 7.658C14.058 44.71 12 43.644 12 41.82V36h-.75A7.25 7.25 0 0 1 4 28.75v-15.5A7.25 7.25 0 0 1 11.25 6zM41 4a5 5 0 1 1 0 10a5 5 0 0 1 0-10");
}

</style>
