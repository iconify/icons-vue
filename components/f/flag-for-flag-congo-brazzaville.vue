<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="u-5xu08kw"/><path class="stz8ael9v"/><path class="d851tibgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-congo-brazzaville" /></template>
<style>
.d851tibgi {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("M7 48.5c1.1 1.7 2.4 3.2 3.8 4.7c1.4 1.4 3 2.7 4.7 3.8L57 15.5A28.7 28.7 0 0 0 48.5 7z");
}

.stz8ael9v {
  fill: var(--svg-color--75a843, #75a843);
  d: path("M32 2C15.4 2 2 15.4 2 32c0 6.1 1.8 11.8 5 16.5h8.5l33.1-33.1V7C43.8 3.8 38.1 2 32 2");
}

.u-5xu08kw {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M57 15.5h-8.5l-33 33V57c4.7 3.1 10.4 5 16.5 5c16.6 0 30-13.4 30-30c0-6.1-1.8-11.8-5-16.5");
}

</style>
