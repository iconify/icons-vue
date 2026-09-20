<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="qx7amqbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:letter-u" /></template>
<style>
.qx7amqbew {
  fill: var(--svg-color--fff, #fff);
  d: path("M8 9.156c0-1.55 1.167-2.418 2.5-2.418s2.5.868 2.5 2.418v10.821c0 2.853 2.055 4.923 5 4.923c2.822 0 5-2.194 5-4.923V9.156c0-1.55 1.168-2.418 2.5-2.418c1.334 0 2.467.868 2.467 2.418v11.069c0 5.209-4.852 9.147-9.967 9.147c-5.178 0-10-3.876-10-9.147z");
}

.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
