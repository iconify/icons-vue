<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="x4h2n29gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:counterclockwise-arrows-button" /></template>
<style>
.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.x4h2n29gr {
  fill: var(--svg-color--fff, #fff);
  d: path("m22.242 22.242l2.829 2.829c-3.905 3.905-10.237 3.904-14.143-.001a9.97 9.97 0 0 1-2.854-8.225l-4.037.367c-.215 3.84 1.128 7.752 4.062 10.687c5.467 5.467 14.333 5.468 19.799 0l2.828 2.828l.849-9.334zM27.899 8.1C22.431 2.633 13.568 2.633 8.1 8.1L5.272 5.272l-.849 9.334l9.334-.849l-2.829-2.829c3.906-3.905 10.236-3.905 14.142 0a9.98 9.98 0 0 1 2.856 8.226l4.036-.366c.216-3.841-1.128-7.753-4.063-10.688");
}

</style>
