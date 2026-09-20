<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4lsoxgig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-check-outline-sharp" /></template>
<style>
.n4lsoxgig {
  fill: currentColor;
  d: path("m10.95 14l4.95-4.95l-1.425-1.4l-3.525 3.525L9.525 9.75L8.1 11.175zM5 21V3h14v18l-7-3zm2-3.05l5-2.15l5 2.15V5H7zM7 5h10z");
}

</style>
