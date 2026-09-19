<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pckfb6jzm"/><path class="pqkjdzbtq"/><circle class="jgxgl9b0v"/><circle class="lnyip1wau"/><path class="v3v11bcpb"/><path class="nhq3yqs_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:artist-palette" /></template>
<style>
.jgxgl9b0v {
  cx: 40.875px;
  cy: 17.808px;
  r: 6.394px;
  fill: var(--svg-color--e45264, #e45264);
}

.lnyip1wau {
  cx: 49.981px;
  cy: 35.613px;
  r: 6.395px;
  fill: var(--svg-color--405967, #405967);
}

.nhq3yqs_v {
  fill: var(--svg-color--e7e6e6, #e7e6e6);
  d: path("M23.482 49.22a6.395 6.395 0 1 1-12.79 0a6.395 6.395 0 0 1 12.79 0");
}

.pckfb6jzm {
  fill: var(--svg-color--c2986b, #c2986b);
  d: path("M5.306 49.865a32 32 0 0 0 3.743 4.532c12.514 12.512 32.795 12.517 45.31 0c12.515-12.513 12.513-32.794-.002-45.31c-12.512-12.507-32.793-12.512-45.31 0C3.903 14.229.912 20.686-.003 27.375l14.247-2.61l-8.941 25.1");
}

.pqkjdzbtq {
  fill: var(--svg-color--02897d, #02897d);
  d: path("M29.875 13.75a6.397 6.397 0 0 1-6.396 6.394a6.397 6.397 0 0 1 0-12.792a6.4 6.4 0 0 1 6.396 6.398");
}

.v3v11bcpb {
  fill: var(--svg-color--ed2e7c, #ed2e7c);
  d: path("M44.06 52.73a6.394 6.394 0 0 1-12.789 0a6.394 6.394 0 1 1 12.789 0");
}

</style>
