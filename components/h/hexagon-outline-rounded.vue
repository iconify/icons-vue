<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlcd3obnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hexagon-outline-rounded" /></template>
<style>
.jlcd3obnh {
  fill: currentColor;
  d: path("M7.95 21q-.55 0-1-.262T6.225 20l-4.05-7q-.275-.475-.275-1t.275-1l4.05-7q.275-.475.725-.737t1-.263h8.1q.55 0 1 .263t.725.737l4.05 7q.275.475.275 1t-.275 1l-4.05 7q-.275.475-.725.738t-1 .262zm0-2h8.1l4.025-7l-4.025-7h-8.1L3.9 12zM12 12");
}

</style>
