<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e09his29d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brackets-dots-fill-round" /></template>
<style>
.e09his29d {
  fill: currentColor;
  d: path("M6 4H5a.997.997 0 0 0-1 1v14a1 1 0 0 0 1 1h1a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h1a1 1 0 0 1 0 2m12-2h1a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3h-1a1 1 0 0 1 0-2h1a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1h-1a1 1 0 0 1 0-2M9 5h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2m-6 6h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2m-6 6h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2");
}

</style>
