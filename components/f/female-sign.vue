<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="cfyr1qm9x"/><path class="s79xwibdl"/><path class="mj1q0nb2l"/><path class="o2olufb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:female-sign" /></template>
<style>
.cfyr1qm9x {
  fill: var(--svg-color--ea596e, #ea596e);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.mj1q0nb2l {
  fill: var(--svg-color--fff, #fff);
  d: path("M18 31.5a1.5 1.5 0 0 1-1.5-1.5v-9a1.5 1.5 0 1 1 3 0v9a1.5 1.5 0 0 1-1.5 1.5");
}

.o2olufb0x {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.875 27.5h-9.75a1.5 1.5 0 1 1 0-3h9.75a1.5 1.5 0 1 1 0 3");
}

.s79xwibdl {
  fill: var(--svg-color--fff, #fff);
  d: path("M18 22.5c-4.687 0-8.5-3.813-8.5-8.5s3.813-8.5 8.5-8.5s8.5 3.813 8.5 8.5s-3.813 8.5-8.5 8.5m0-14c-3.033 0-5.5 2.468-5.5 5.5s2.467 5.5 5.5 5.5s5.5-2.468 5.5-5.5s-2.467-5.5-5.5-5.5");
}

</style>
