<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukuqz5b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-open-sharp" /></template>
<style>
.ukuqz5b-i {
  fill: currentColor;
  d: path("M21.95 22.375L19 19.425v2.225h-2V16h5.65v2H20.4l2.95 2.95zM13 9h5l-5-5zM4 22V2h10l6 6v6h-5v8z");
}

</style>
