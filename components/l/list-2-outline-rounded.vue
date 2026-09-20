<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqcz6qbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:list-2-outline-rounded" /></template>
<style>
.aqcz6qbuj {
  fill: currentColor;
  d: path("M8.25 17q-.213 0-.356-.144t-.144-.357t.144-.356T8.25 16h7.5q.213 0 .356.144t.144.357t-.144.356t-.356.143zM4.5 12.5q-.213 0-.356-.144T4 11.999t.144-.356t.356-.143h15q.213 0 .356.144t.144.357t-.144.356t-.356.143zM8.25 8q-.213 0-.356-.144t-.144-.357t.144-.356T8.25 7h7.5q.213 0 .356.144t.144.357t-.144.356T15.75 8z");
}

</style>
