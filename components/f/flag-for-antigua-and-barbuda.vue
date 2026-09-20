<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="mh5zr4bfz"/><path class="ey7c84bki"/><path class="kirw4fbqt"/><path class="an-oixbnq"/><path class="z82bkcbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-antigua-and-barbuda" /></template>
<style>
.an-oixbnq {
  fill: var(--svg-color--0072c6, #0072C6);
  d: path("M10.279 15H6.923l4.154 6h13.846l4.154-6h-3.356z");
}

.ey7c84bki {
  fill: var(--svg-color--141414, #141414);
  d: path("M10.279 15l-.105-.022l3.988-.827l-3.392-2.417l3.977.889l-2.28-3.64l3.36 2.47l-.821-4.308l2.232 3.675L18 6.5l.763 4.321l2.232-3.675l-.821 4.308l3.36-2.47l-2.28 3.64l3.977-.889l-3.392 2.417l3.988.827l-.106.021h3.356l5.956-8.603A3.988 3.988 0 0 0 32 5H4A3.988 3.988 0 0 0 .967 6.397L6.923 15h3.356z");
}

.kirw4fbqt {
  fill: var(--svg-color--fcd116, #FCD116);
  d: path("M25.826 14.978l-3.988-.827l3.392-2.417l-3.976.889l2.28-3.64l-3.36 2.47l.821-4.308l-2.232 3.676L18 6.5l-.763 4.321l-2.232-3.676l.821 4.308l-3.36-2.47l2.28 3.64l-3.976-.889l3.392 2.417l-3.988.827l.105.022h15.442z");
}

.mh5zr4bfz {
  fill: var(--svg-color--fff, #FFF);
  d: path("M11.077 21L18 31l6.923-10z");
}

.z82bkcbis {
  fill: var(--svg-color--ce1126, #CE1126);
  d: path("M29.077 15l-4.154 6L18 31h14a4 4 0 0 0 4-4V9c0-.995-.366-1.903-.967-2.603L29.077 15zM6.923 15L.967 6.397A3.982 3.982 0 0 0 0 9v18a4 4 0 0 0 4 4h14l-6.923-10l-4.154-6z");
}

</style>
