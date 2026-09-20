<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="bjgoxobag"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:frax-background" /></template>
<style>
.bjgoxobag {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.16 15.739c-.208.224-.576.624-.997 1.066A53 53 0 0 0 4 18.048c.64.64 1.29 1.275 1.947 1.893l.069.059l1.008-1.067l1.11-1.173a6.93 6.93 0 0 0 7.68.032l.031.037q1.104 1.08 2.224 2.144c.022.006 1.936-2.021 1.931-2.042c0-.011-1.317-1.286-2.123-2.054l-.074-.08a6.93 6.93 0 0 0-.011-7.605l.997-1.061q.573-.586 1.115-1.2c-.016-.043-1.979-1.92-2.005-1.92c-.016 0-.512.512-1.099 1.13c-.448.48-.837.886-1.003 1.056a6.93 6.93 0 0 0-7.493-.064l-.07-.074l-.96-.928l-.266-.251l-.715-.693L6.101 4l-.949 1.013a36 36 0 0 0-.96 1.03c-.005.01.464.48 1.045 1.04l1.04 1.002a6.93 6.93 0 0 0-.117 7.654M16.267 12a4.267 4.267 0 1 1-8.534 0a4.267 4.267 0 0 1 8.534 0");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
