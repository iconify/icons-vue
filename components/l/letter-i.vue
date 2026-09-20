<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="ub3z9kbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:letter-i" /></template>
<style>
.ub3z9kbpz {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.675 9.156c0-1.55.992-2.418 2.326-2.418c1.333 0 2.325.868 2.325 2.418v17.611c0 1.551-.992 2.418-2.325 2.418s-2.326-.867-2.326-2.418z");
}

.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
