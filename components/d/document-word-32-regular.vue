<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k1l31ljgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-word-32-regular" /></template>
<style>
.k1l31ljgo {
  fill: currentColor;
  d: path("M14.25 15A2.75 2.75 0 0 1 17 17.75v9.5A2.75 2.75 0 0 1 14.25 30h-9.5A2.75 2.75 0 0 1 2 27.25v-9.5A2.75 2.75 0 0 1 4.75 15zm2.818-13a3.25 3.25 0 0 1 2.298.952l6.682 6.682c.61.61.952 1.436.952 2.298V26.75A3.25 3.25 0 0 1 23.75 30h-6.262c.477-.56.81-1.245.945-2h5.317c.69 0 1.25-.56 1.25-1.25V13h-5.75A3.25 3.25 0 0 1 16 9.75V4H8.25C7.56 4 7 4.56 7 5.25v8.25H5V5.25A3.25 3.25 0 0 1 8.25 2zm-4.043 15.918l-1.141 6.049l-1.218-6.049H8.28l-1.164 6.049l-1.17-6.049H4l1.897 9.165H8.28l1.22-5.5l1.166 5.5l2.36-.001L15 17.917zM18 9.75c0 .69.56 1.25 1.25 1.25h5.336L18 4.414z");
}

</style>
