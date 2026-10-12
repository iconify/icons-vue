<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9a56rb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:certificate-seal" /></template>
<style>
.l9a56rb5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.25 10.54V4.75a2 2 0 0 0-2-2h-8.5a2 2 0 0 0-2 2v12.5a2 2 0 0 0 2 2h5.15a6.5 6.5 0 0 1 5.35-8.71M7 7h6m-6 3.5h3m7.4 3.05l.39.29q.4.3.89.37l.48.07q.49.07.56.56l.07.48q.07.49.37.89l.29.39q.3.4 0 .8l-.29.39q-.3.4-.37.89l-.07.48q-.07.49-.56.56l-.48.07q-.49.07-.89.37l-.39.29q-.4.3-.8 0l-.39-.29q-.4-.3-.89-.37l-.48-.07q-.49-.07-.56-.56l-.07-.48q-.07-.49-.37-.89l-.29-.39q-.3-.4 0-.8l.29-.39q.3-.4.37-.89l.07-.48q.07-.49.56-.56l.48-.07q.49-.07.89-.37l.39-.29q.4-.3.8 0");
}

</style>
