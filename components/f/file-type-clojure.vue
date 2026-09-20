<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e9hye41ik"/><path class="bpo-f8b0c"/><path class="swb950wwj"/><path class="w7u11f-3t"/><path class="hizu8xb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-clojure" /></template>
<style>
.bpo-f8b0c {
  fill: var(--svg-color--91dc47, #91dc47);
  d: path("M15.488 16.252c-.126.273-.265.579-.408.9a23 23 0 0 0-1.28 3.453a5.2 5.2 0 0 0-.119 1.155q0 .262.024.542a6.66 6.66 0 0 0 4.413.067a4 4 0 0 1-.44-.466c-.9-1.146-1.4-2.827-2.194-5.652m-3.315-5.695a6.677 6.677 0 0 0-.077 10.881c.411-1.71 1.44-3.276 2.983-6.415c-.092-.252-.2-.527-.313-.817a10.2 10.2 0 0 0-1.6-2.882a4.4 4.4 0 0 0-1-.767");
}

.e9hye41ik {
  fill: var(--svg-color--fff, #fff);
  d: path("M16 2a14 14 0 1 0 14 14A14.016 14.016 0 0 0 16 2");
}

.hizu8xb7h {
  fill: var(--svg-color--5881d8, #5881d8);
  d: path("M16.013 3.372A12.63 12.63 0 0 0 5.731 8.656a6.43 6.43 0 0 1 3.48-1.009a6.8 6.8 0 0 1 3.182.772q.2.116.386.246a8.038 8.038 0 0 1 11.273 7.358a8 8 0 0 1-2.391 5.719a10 10 0 0 0 1.143.064a6.24 6.24 0 0 0 4.051-1.263a5.35 5.35 0 0 0 1.7-2.906A12.632 12.632 0 0 0 16.013 3.372");
}

.swb950wwj {
  fill: var(--svg-color--63b132, #63b132);
  d: path("M21.84 23.7a11 11 0 0 1-2.257-.471a8.036 8.036 0 0 1-8.867-13.247a6 6 0 0 0-1.4-.171c-2.358.022-4.848 1.327-5.884 4.852a6.6 6.6 0 0 0-.074 1.361a12.649 12.649 0 0 0 23 7.274a14.7 14.7 0 0 1-3.448.459a9 9 0 0 1-1.07-.057");
}

.w7u11f-3t {
  fill: var(--svg-color--90b4fe, #90b4fe);
  d: path("M19.463 21.244a3.5 3.5 0 0 0 .5.172a6.69 6.69 0 0 0 2.737-5.393a6.68 6.68 0 0 0-8.79-6.348c1.358 1.548 2.011 3.761 2.643 6.181s.2.673.547 1.562a15.4 15.4 0 0 0 1.363 2.788a2.9 2.9 0 0 0 1 1.036");
}

</style>
