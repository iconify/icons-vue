<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="d2krg-08m"/><path class="q1zpp1cfx"/><path class="ho34xsbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-samoa" /></template>
<style>
.d2krg-08m {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 2v30H2c0 16.6 13.4 30 30 30s30-13.4 30-30S48.6 2 32 2");
}

.ho34xsbhs {
  fill: var(--svg-color--fff, #fff);
  d: path("m19 13.1l1.2.9l-.4-1.5l1.2-1h-1.5L19 10l-.5 1.5H17l1.2 1l-.4 1.5zm0 14l1.2.9l-.4-1.5l1.2-1h-1.5L19 24l-.5 1.5H17l1.2 1l-.4 1.5zm-5-9l1.2.9l-.4-1.5l1.2-1h-1.5L14 15l-.5 1.5H12l1.2 1l-.4 1.5zm10 0l1.2.9l-.4-1.5l1.2-1h-1.5L24 15l-.5 1.5H22l1.2 1l-.4 1.5zm-2 4.4l.6.5l-.2-.8l.6-.4h-.8L22 21l-.2.8H21l.6.4l-.2.8z");
}

.q1zpp1cfx {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M32 2C15.4 2 2 15.4 2 32h30z");
}

</style>
