<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="cqv3tjbmq"/><path class="ut0hucayh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:gitlab-logo-duotone" /></template>
<style>
.cqv3tjbmq {
  d: path("M220.23 110.84L128 176l-92.23-65.16L53.5 43a3.93 3.93 0 0 1 7.5-.38L80.65 96h94.7L195 42.62a3.93 3.93 0 0 1 7.53.38Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cuyn6tgcc {
  fill: currentColor;
}

.ut0hucayh {
  d: path("M230.15 117.1L210.25 41a11.94 11.94 0 0 0-22.79-1.11L169.78 88H86.22L68.54 39.87A11.94 11.94 0 0 0 45.75 41l-19.9 76.1a57.19 57.19 0 0 0 22 61l73.27 51.76a11.91 11.91 0 0 0 13.74 0l73.27-51.76a57.19 57.19 0 0 0 22.02-61M58 57.5l15.13 41.26a8 8 0 0 0 7.51 5.24h94.72a8 8 0 0 0 7.51-5.24L198 57.5l13.07 50L128 166.21L44.9 107.5Zm-17.32 66.61L114.13 176l-20.72 14.65L57.09 165a41.06 41.06 0 0 1-16.41-40.89m87.32 91l-20.73-14.65L128 185.8l20.73 14.64ZM198.91 165l-36.32 25.66L141.87 176l73.45-51.9a41.06 41.06 0 0 1-16.41 40.9");
}

</style>
