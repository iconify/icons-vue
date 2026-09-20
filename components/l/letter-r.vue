<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="ki5prcbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:letter-r" /></template>
<style>
.ki5prcbtk {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.777 9.342c0-1.488.837-2.418 2.388-2.418h5.457c4.775 0 7.72 2.14 7.72 7.007c0 3.411-2.573 5.364-5.736 5.86l5.272 5.644c.433.465.619.93.619 1.364c0 1.209-.961 2.387-2.324 2.387c-.559 0-1.303-.217-1.799-.806l-6.883-8.341h-.062v6.728c0 1.551-.992 2.418-2.326 2.418s-2.326-.867-2.326-2.418zm4.651 7.348h3.193c1.705 0 2.884-1.023 2.884-2.759c0-1.767-1.18-2.729-2.884-2.729h-3.193z");
}

.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
