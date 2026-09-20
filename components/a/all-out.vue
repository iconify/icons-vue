<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2b8xqbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:all-out" /></template>
<style>
.v2b8xqbez {
  fill: currentColor;
  d: path("M3 21v-5h2v3h3v2zm13 0v-2h3v-3h2v5zm-8.95-4.05Q5 14.9 5 12t2.05-4.95T12 5t4.95 2.05T19 12t-2.05 4.95T12 19t-4.95-2.05M3 8V3h5v2H5v3zm16 0V5h-3V3h5v5z");
}

</style>
