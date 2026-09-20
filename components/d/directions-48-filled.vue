<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l02sz6b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:directions-48-filled" /></template>
<style>
.l02sz6b2h {
  fill: currentColor;
  d: path("M19.584 4.83a6.25 6.25 0 0 1 8.839 0l14.753 14.753a6.25 6.25 0 0 1 0 8.839L28.423 43.175a6.25 6.25 0 0 1-8.84 0L4.832 28.422a6.25 6.25 0 0 1 0-8.84zm7.55 8.036a1.25 1.25 0 0 0-1.767 1.768L28.733 18h-4.482A6.25 6.25 0 0 0 18 24.25v7.5a1.25 1.25 0 0 0 2.5 0v-7.5a3.75 3.75 0 0 1 3.75-3.75h4.482l-3.366 3.366a1.25 1.25 0 1 0 1.768 1.768l5.5-5.5a1.25 1.25 0 0 0 0-1.768z");
}

</style>
