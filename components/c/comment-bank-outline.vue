<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6ek6_mfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:comment-bank-outline" /></template>
<style>
.v6ek6_mfu {
  fill: currentColor;
  d: path("M12.5 11V4H4v13.125L5.15 16H20V4h-2.5v7L15 9.5zM2 22V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18H6zM4 4v12z");
}

</style>
