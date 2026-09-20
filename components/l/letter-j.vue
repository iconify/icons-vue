<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="gfb0m1cch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:letter-j" /></template>
<style>
.gfb0m1cch {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.102 22.799c0 5.209-3.318 6.573-6.139 6.573c-2.14 0-5.705-.837-5.705-3.534c0-.838.713-1.892 1.736-1.892c1.24 0 2.325 1.147 3.721 1.147c1.736 0 1.736-1.613 1.736-2.605V9.156c0-1.55.993-2.418 2.325-2.418c1.334 0 2.326.868 2.326 2.418z");
}

.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
