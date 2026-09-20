<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="r9rioofmx"/><path class="nctwugbqo"/><path class="g58e_2-1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:left-luggage" /></template>
<style>
.g58e_2-1u {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M32 10H4a2 2 0 0 0-2 2v20a2 2 0 0 0 2 2h28a2 2 0 0 0 2-2V12a2 2 0 0 0-2-2m0 21a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V13a1 1 0 0 1 1-1h26a1 1 0 0 1 1 1zM24 4h-6.35a3.49 3.49 0 0 0-3.15-2a3.5 3.5 0 1 0 0 7a3.49 3.49 0 0 0 3.45-3h1.719c.247.926.747 2 1.331 2s1.084-1.074 1.331-2H23c0 1.104.448 2 1 2s1-1 1-3c0-1.105-.448-1-1-1M13.5 7a1.5 1.5 0 1 1-.001-2.999A1.5 1.5 0 0 1 13.5 7");
}

.nctwugbqo {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M26 17h-1v13h1a2 2 0 0 0 2-2v-9a2 2 0 0 0-2-2m-16 0a2 2 0 0 0-2 2v9a2 2 0 0 0 2 2h1V17zm12 0v-2a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v2h-1v13h10V17zm-6-1a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v1h-4z");
}

.r9rioofmx {
  fill: var(--svg-color--269, #269);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
