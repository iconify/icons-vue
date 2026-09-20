<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="fuodxab2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:letter-f" /></template>
<style>
.fuodxab2d {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.513 9.342c0-1.271.868-2.418 2.419-2.418h7.937c1.365 0 2.078 1.054 2.078 2.14c0 1.054-.683 2.139-2.078 2.139h-5.705v4.527h4.806c1.488 0 2.232 1.054 2.232 2.108c0 1.085-.744 2.17-2.232 2.17h-4.806v6.76c0 1.551-.992 2.418-2.326 2.418s-2.326-.867-2.326-2.418z");
}

.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
