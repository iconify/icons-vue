<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="mval8nb0n"/><path class="c-ugn6paq"/><path class="s5ctncczj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-maldives" /></template>
<style>
.c-ugn6paq {
  fill: var(--svg-color--007e3a, #007e3a);
  d: path("M6 11h24v14H6z");
}

.mval8nb0n {
  fill: var(--svg-color--d21034, #d21034);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.s5ctncczj {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.64 22.344q.419-.001.814-.077a4.344 4.344 0 0 1 0-8.532a4.344 4.344 0 1 0-.814 8.609");
}

</style>
