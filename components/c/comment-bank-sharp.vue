<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl6lqk5vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:comment-bank-sharp" /></template>
<style>
.fl6lqk5vz {
  fill: currentColor;
  d: path("M12.5 11L15 9.5l2.5 1.5V4h-5zM2 22V2h20v16H6z");
}

</style>
