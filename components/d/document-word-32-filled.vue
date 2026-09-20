<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j-koaub0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-word-32-filled" /></template>
<style>
.j-koaub0f {
  fill: currentColor;
  d: path("M14.25 15A2.75 2.75 0 0 1 17 17.75v9.5A2.75 2.75 0 0 1 14.25 30h-9.5A2.75 2.75 0 0 1 2 27.25v-9.5A2.75 2.75 0 0 1 4.75 15zM16 9.75A3.25 3.25 0 0 0 19.25 13H27v13.75A3.25 3.25 0 0 1 23.75 30h-6.262a4.23 4.23 0 0 0 1.012-2.75v-9.5a4.25 4.25 0 0 0-4.25-4.25H5V5.25A3.25 3.25 0 0 1 8.25 2H16zm-2.975 8.168l-1.141 6.049l-1.218-6.049H8.28l-1.164 6.049l-1.17-6.049H4l1.897 9.165H8.28l1.22-5.5l1.166 5.5l2.36-.001L15 17.917zM18 2.137a3.25 3.25 0 0 1 1.366.815l6.682 6.682c.384.384.662.855.815 1.366H19.25c-.69 0-1.25-.56-1.25-1.25z");
}

</style>
