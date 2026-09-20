<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="cgxt-_ekh"/><path class="h96bx56_v"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kas-background" /></template>
<style>
.cgxt-_ekh {
  fill: var(--svg-color--71c9bb, #71c9bb);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.h96bx56_v {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.24 4.04a5.6 5.6 0 0 0-2.272.781c-.683.424-2.842 2.527-3.285 3.2c-.588.894-.64 1.13-.677 2.918c-.029 1.689.047 2.691.273 3.482c.258.903.527 1.28 1.976 2.785c1.482 1.539 1.957 1.939 2.635 2.212a7.23 7.23 0 0 0 4.635.352c2.48-.644 4.362-2.14 5.458-4.328q.54-1.185.927-2.428c.136-.48.113-1.892-.038-2.461c-.48-1.807-1.115-3.007-2.197-4.132a8.24 8.24 0 0 0-4.14-2.277a16.7 16.7 0 0 0-3.295-.104m3.878 3.407l.705 4.555c-.211 1.421-.546 3.054-.743 4.47l-1.675-.39c.245-1.549.47-3.03.442-3.059c-.014-.014-.07 0-.122.047c-.706.55-3.374 2.55-3.374 2.55L8.33 14.326c.49-.404 3.035-2.4 3.035-2.4L8.33 9.5l.946-1.285l3.576 2.612s-.362-2.763-.433-3.068l1.694-.31z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
