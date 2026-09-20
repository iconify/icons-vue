<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3p938b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-multiple-person-24-regular" /></template>
<style>
.g3p938b5t {
  fill: currentColor;
  d: path("M17.015 6.41a7.504 7.504 0 0 1 4.343 10.264c.253 1.008.51 2.1.672 2.803a1.244 1.244 0 0 1-1.468 1.5a135 135 0 0 1-2.913-.64a7.5 7.5 0 0 1-3.088.663c-1.969 0-3.76-.76-5.1-2.001l.1.001c.718 0 1.416-.09 2.082-.257a6 6 0 0 0 2.919.757c.96 0 1.866-.225 2.67-.625l.243-.121l.264.062c.922.22 1.965.446 2.74.61c-.175-.75-.414-1.755-.642-2.65l-.07-.276l.13-.253a6 6 0 0 0 .665-2.747a6 6 0 0 0-2.748-5.042a8.5 8.5 0 0 0-.8-2.048M9.56 3a7.5 7.5 0 1 1-3.086 14.337c-1.028.245-2.18.522-2.931.702a1.25 1.25 0 0 1-1.504-1.524l.725-2.841A7.5 7.5 0 0 1 9.562 3m0 1.5a6 6 0 0 0-5.335 8.747l.13.253l-.07.275l-.69 2.708l2.788-.667l.264-.062l.244.121A6 6 0 1 0 9.562 4.5M11.5 11a1.5 1.5 0 0 1 1.5 1.5C13 14 11.5 15 9.5 15S6 14 6 12.5A1.5 1.5 0 0 1 7.5 11zm-2-5a2 2 0 1 1 0 4a2 2 0 0 1 0-4");
}

</style>
