<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="w1dgew86a"/><path class="snqx7pl7d"/><path class="ti19ytvcr"/><path class="i3i8qju6l"/><path class="jqkribb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-jordan" /></template>
<style>
.i3i8qju6l {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("M1.351 6.004A4 4 0 0 0 0 9v18c0 1.193.522 2.264 1.351 2.997L17.5 18z");
}

.jqkribb0r {
  fill: var(--svg-color--fff, #fff);
  d: path("m6.627 19.338l1.056.976l-.105-1.435L9 18.662l-1.187-.812l.717-1.247l-1.375.421l-.528-1.338l-.528 1.338l-1.375-.421l.716 1.247l-1.186.812l1.421.217l-.104 1.435z");
}

.snqx7pl7d {
  fill: var(--svg-color--007a3d, #007a3d);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-4.5H0z");
}

.ti19ytvcr {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 13.5h36v9H0z");
}

.w1dgew86a {
  fill: var(--svg-color--141414, #141414);
  d: path("M32 5H4a4 4 0 0 0-4 4v4.5h36V9a4 4 0 0 0-4-4");
}

</style>
