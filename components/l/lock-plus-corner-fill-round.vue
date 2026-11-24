<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxvcv6nqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-plus-corner-fill-round" /></template>
<style>
.gxvcv6nqj {
  fill: currentColor;
  d: path("M7 8.099V7a5 5 0 0 1 10 0v1.098a5 5 0 0 1 1.5.572a4.9 4.9 0 0 1 1.83 1.83a.997.997 0 0 1-.366 1.366a1 1 0 0 1-.5.134H15c-.796 0-1.559.316-2.121.879A3 3 0 0 0 12 15v6a1 1 0 0 1-1 1H8a5 5 0 0 1-5-5v-4a5.01 5.01 0 0 1 4-4.901M15 8V7a3 3 0 1 0-6 0v1Zm4 7v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2h-2a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0");
}

</style>
