<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dyxwr7jjo"/><path class="w6em3319z"/><path class="as9o85buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-czechia" /></template>
<style>
.as9o85buf {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M32.416 32L4.486 11.5C1.513 13.407 0 16.942 0 21v22c0 3.883 1.385 7.289 4.11 9.246l28.344-20.219z");
}

.dyxwr7jjo {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M32.454 32.03L4.11 52.25c1.538 1.106 3.499 1.754 5.89 1.754h44c6.627 0 10-4.925 10-11v-11H32.416z");
}

.w6em3319z {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M54 10H10c-2.201 0-4.04.553-5.514 1.5L32.416 32H64V21c0-6.075-3.373-11-10-11");
}

</style>
