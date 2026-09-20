<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="h-1f88bhr"/><path class="oijkx8qiv"/><path class="oeaykpxwa"/><path class="kwmz4jboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-bahamas" /></template>
<style>
.h-1f88bhr {
  fill: var(--svg-color--00abc9, #00abc9);
  d: path("M1.364 29.987A3.97 3.97 0 0 0 4 31h28a4 4 0 0 0 4-4v-4.5H11.442z");
}

.kwmz4jboz {
  fill: var(--svg-color--141414, #141414);
  d: path("m17.5 18l-6.058-4.5L1.364 6.013A3.97 3.97 0 0 0 0 9v18c0 1.194.534 2.254 1.364 2.987L11.442 22.5z");
}

.oeaykpxwa {
  fill: var(--svg-color--00abc9, #00abc9);
  d: path("M32 5H4c-1.015 0-1.931.39-2.636 1.013L11.442 13.5H36V9a4 4 0 0 0-4-4");
}

.oijkx8qiv {
  fill: var(--svg-color--fae042, #fae042);
  d: path("m17.5 18l-6.058 4.5H36v-9H11.442z");
}

</style>
