<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="r9rioofmx"/><path class="h0xxz-bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:baggage-claim" /></template>
<style>
.h0xxz-bnu {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M29 8h-2v18h2a2 2 0 0 0 2-2V10a2 2 0 0 0-2-2M7 8a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h2V8zm16 0V5a2 2 0 0 0-2-2h-6a2 2 0 0 0-2 2v3h-2v18h14V8zm-8-2a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2h-6zm18 22H3a1 1 0 1 0 0 2h1a2 2 0 0 0 4 0h2a2 2 0 0 0 4 0h2a2 2 0 0 0 4 0h2a2 2 0 0 0 4 0h2a2 2 0 0 0 4 0h1a1 1 0 1 0 0-2");
}

.r9rioofmx {
  fill: var(--svg-color--269, #269);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
