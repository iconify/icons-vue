<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kguejje_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-search-corner-fill-round" /></template>
<style>
.kguejje_m {
  fill: currentColor;
  d: path("m12.632 13.157l-.938-.877a3.825 3.825 0 0 0-5.401.013L2 16.586V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v4a1 1 0 0 1-1 1h-6c-.927 0-1.8.424-2.368 1.157M15 10a2 2 0 1 0 .001-3.999A2 2 0 0 0 15 10m-4.683 3.73l1.461 1.366a1 1 0 0 0 .222.157V21a1 1 0 0 1-1 1H7a4.99 4.99 0 0 1-4.584-3.001l5.291-5.292a1.83 1.83 0 0 1 1.982-.402c.259.105.434.244.628.425m11.004 6.177l1.386 1.386a.999.999 0 1 1-1.414 1.414l-1.386-1.386a3.83 3.83 0 1 1 1.414-1.414m-2.028-.614a1.829 1.829 0 1 0-2.587-2.586a1.829 1.829 0 0 0 2.587 2.586");
}

</style>
