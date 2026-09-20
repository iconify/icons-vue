<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="ztry2tbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:keycap-8" /></template>
<style>
.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.ztry2tbjb {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.343 22.303c0-2.48 1.364-4.309 3.317-5.364c-1.457-1.054-2.356-2.48-2.356-4.434c0-3.628 3.008-5.953 6.697-5.953c3.596 0 6.729 2.294 6.729 5.953c0 1.736-.869 3.473-2.389 4.434c2.109 1.055 3.318 2.977 3.318 5.364c0 4.31-3.504 7.069-7.659 7.069c-4.277 0-7.657-2.915-7.657-7.069m4.837-.311c0 1.582.93 3.102 2.821 3.102c1.768 0 2.822-1.52 2.822-3.102c0-1.953-1.116-3.1-2.822-3.1c-1.797 0-2.821 1.364-2.821 3.1m.589-8.991c0 1.395.807 2.356 2.232 2.356s2.264-.961 2.264-2.356c0-1.333-.807-2.357-2.264-2.357s-2.232 1.024-2.232 2.357");
}

</style>
