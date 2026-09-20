<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="wr0uf2byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:letter-t" /></template>
<style>
.wr0uf2byi {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.676 11.203h-3.38c-1.488 0-2.108-1.085-2.108-2.139c0-1.085.775-2.14 2.108-2.14h11.411c1.332 0 2.108 1.054 2.108 2.14c0 1.054-.619 2.139-2.108 2.139h-3.381v15.565c0 1.551-.992 2.418-2.325 2.418s-2.325-.867-2.325-2.418z");
}

.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
