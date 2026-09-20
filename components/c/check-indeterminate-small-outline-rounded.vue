<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh6_vvbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:check-indeterminate-small-outline-rounded" /></template>
<style>
.vh6_vvbig {
  fill: currentColor;
  d: path("M7.5 12.5q-.213 0-.356-.144T7 11.999t.144-.356t.356-.143h9q.213 0 .356.144t.144.357t-.144.356t-.356.143z");
}

</style>
