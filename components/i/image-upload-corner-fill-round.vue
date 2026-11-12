<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s91nwbbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-upload-corner-fill-round" /></template>
<style>
.s91nwbbrf {
  fill: currentColor;
  d: path("M21 12h-6c-.927 0-1.8.424-2.368 1.157l-.938-.877a3.825 3.825 0 0 0-5.401.013L2 16.586V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v4a1 1 0 0 1-1 1m-6-2a2 2 0 1 0 .001-3.999A2 2 0 0 0 15 10m-4.683 3.73l1.461 1.366a1 1 0 0 0 .222.157V21a1 1 0 0 1-1 1H7a4.99 4.99 0 0 1-4.584-3.001l5.291-5.292a1.83 1.83 0 0 1 1.982-.402c.259.105.434.244.628.425m9.976 4.977L19 17.414V21a1 1 0 0 1-2 0v-3.586l-1.293 1.293a.999.999 0 1 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414");
}

</style>
