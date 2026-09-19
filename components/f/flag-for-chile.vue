<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g-95lijpf"/><path class="c0g60pb-k"/><path class="q1zpp1cfx"/><path class="h29jztb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-chile" /></template>
<style>
.c0g60pb-k {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M32 2c16.6 0 30 13.4 30 30H32z");
}

.g-95lijpf {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M2 32c0 16.6 13.4 30 30 30s30-13.4 30-30z");
}

.h29jztb9n {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("m20 21.7l4.9 3.3l-1.8-5.3l4.9-3.5h-6.1L20 11l-1.8 5.2H12l4.9 3.5l-1.8 5.3z");
}

.q1zpp1cfx {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M32 2C15.4 2 2 15.4 2 32h30z");
}

</style>
