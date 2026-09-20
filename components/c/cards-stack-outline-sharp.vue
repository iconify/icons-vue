<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="temce00vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cards-stack-outline-sharp" /></template>
<style>
.temce00vd {
  fill: currentColor;
  d: path("M10 9h8V7h-8zm0 3h5v-2h-5zm2.325 6h6.7v1.1l-15.55 2.15L1.75 8.35l1.975-.225L5.25 19zM6 16.1V3h16v13.1zm2-2h12V5H8zm0 0V5zM5.25 19");
}

</style>
