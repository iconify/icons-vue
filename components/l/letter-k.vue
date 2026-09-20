<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="xdprb6bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:letter-k" /></template>
<style>
.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.xdprb6bso {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.925 9.032c0-1.271.93-2.294 2.325-2.294c1.333 0 2.325.868 2.325 2.294v6.697l7.627-8.124c.342-.372.93-.868 1.799-.868c1.178 0 2.295.899 2.295 2.232c0 .806-.496 1.457-1.52 2.48l-5.861 5.767l7.162 7.473c.744.744 1.303 1.426 1.303 2.357c0 1.457-1.146 2.139-2.418 2.139c-.898 0-1.488-.526-2.357-1.457l-8.031-8.682v7.906c0 1.21-.93 2.232-2.325 2.232c-1.333 0-2.325-.867-2.325-2.232V9.032z");
}

</style>
