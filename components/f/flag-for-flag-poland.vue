<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="c6bgvmbcy"/><path class="vretevbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-poland" /></template>
<style>
.c6bgvmbcy {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M32 2c16.6 0 30 13.4 30 30H2C2 15.4 15.4 2 32 2");
}

.vretevbvp {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 62C15.4 62 2 48.6 2 32h60c0 16.6-13.4 30-30 30");
}

</style>
