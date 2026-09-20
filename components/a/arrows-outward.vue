<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv8ywjmee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrows-outward" /></template>
<style>
.cv8ywjmee {
  fill: currentColor;
  d: path("m17 17l-1.4-1.4l2.575-2.6H13v-2h5.175L15.6 8.4L17 7l5 5zM7 17l-5-5l5-5l1.4 1.4L5.825 11H11v2H5.825L8.4 15.6z");
}

</style>
