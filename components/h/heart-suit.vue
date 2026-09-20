<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="wvyw_rbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:heart-suit" /></template>
<style>
.wvyw_rbfl {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M2.067 11.319C2.067 2.521 14.251-.74 18 9.445C21.749-.741 33.933 2.52 33.933 11.319C33.933 20.879 18 33 18 33S2.067 20.879 2.067 11.319");
}

</style>
