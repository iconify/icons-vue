<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k5zqojmot"/><path class="qmaj7_bne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:droplets-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k5zqojmot {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.419 2.186a1 1 0 0 1 1.162 0a11 11 0 0 1 1.673 1.55c1.323 1.513 2.271 3.55 1.431 5.536a4 4 0 0 1-.857 1.271A4 4 0 0 1 14 7.714c0-1.502.783-2.877 1.747-3.98q.527-.6 1.133-1.118q.26-.227.539-.43m-10 5.143a1 1 0 0 1 1.162 0c.296.212.577.445.853.681c1.46 1.252 2.817 2.782 3.68 4.508C13.654 13.6 14 14.785 14 16a5.97 5.97 0 0 1-1.757 4.243A5.98 5.98 0 0 1 8 22a6 6 0 0 1-6-6c.001-2.339 1.248-4.48 2.747-6.194a18 18 0 0 1 1.821-1.797c.275-.236.555-.469.851-.68");
}

.qmaj7_bne {
  d: path("M18.581 2.186c.188.134.365.281.54.431c.924.792 1.758 1.736 2.305 2.83c.352.704.574 1.476.574 2.267a4 4 0 0 1-7.685 1.558c-.84-1.987.108-4.024 1.432-5.538q.527-.6 1.133-1.118q.26-.227.539-.43a1 1 0 0 1 1.162 0M18 4.294c-.921.831-2 2.121-2 3.42a2 2 0 1 0 4 0c0-1.299-1.079-2.589-2-3.42");
}

</style>
