<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qf-ocph5a"/><path class="k73axdbnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hzn" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k73axdbnp {
  fill: var(--svg-color--2ad4b7, #2ad4b7);
  d: path("M17.4 8.4L12 3l-9 9l2.7 2.7l1.8-1.8l-.9-.9L12 6.6l1.8 1.8l-.9.9l-.4-.45v2.65h2.65l-.45-.4z");
}

.qf-ocph5a {
  fill: var(--svg-color--37f, #37f);
  d: path("m21 12l-2.7-2.7l-1.8 1.8l.9.9l-5.4 5.4l-1.8-1.8l.9-.9l.4.45V12.5H8.85l.45.4l-2.7 2.7L12 21z");
}

</style>
