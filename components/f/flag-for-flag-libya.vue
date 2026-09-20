<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="q4ceig-ee"/><path class="b36zl9bez"/><path class="vkot_9bta"/><path class="w-3ggobyg"/><path class="un9rv1_fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-libya" /></template>
<style>
.b36zl9bez {
  fill: var(--svg-color--e70013, #e70013);
  d: path("M32 5H4a4 4 0 0 0-4 4v3h36V9a4 4 0 0 0-4-4");
}

.q4ceig-ee {
  fill: var(--svg-color--141414, #141414);
  d: path("M0 24h36V12H0zm21.25-8.298l1.032 1.42l1.67-.542L22.92 18l1.032 1.42l-1.67-.542l-1.032 1.42v-1.756L19.58 18l1.67-.543zM18 14.75c.902 0 1.718.368 2.307.961a2.8 2.8 0 0 0-1.649-.535a2.824 2.824 0 1 0 1.649 5.113A3.25 3.25 0 1 1 18 14.75");
}

.un9rv1_fw {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.25 18.542v1.756l1.032-1.42l1.67.542L22.92 18l1.032-1.42l-1.67.542l-1.032-1.42v1.755L19.58 18z");
}

.vkot_9bta {
  fill: var(--svg-color--239e46, #239e46);
  d: path("M32 31H4a4 4 0 0 1-4-4v-3h36v3a4 4 0 0 1-4 4");
}

.w-3ggobyg {
  fill: var(--svg-color--fff, #fff);
  d: path("M18 21.25c.902 0 1.718-.368 2.307-.961a2.8 2.8 0 0 1-1.649.535a2.824 2.824 0 1 1 1.649-5.113A3.25 3.25 0 1 0 18 21.25");
}

</style>
