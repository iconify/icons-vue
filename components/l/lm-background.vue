<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="rjaxoxbhu"/><path class="bbhminz5i"/><path class="qhgf1-bky"/><path class="ms1h7-g1v"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lm-background" /></template>
<style>
.bbhminz5i {
  fill: var(--svg-color--fff, #fff);
  d: path("m5.263 8.21l2.526 1.264v4.632l-2.526 1.263zm13.474.422L16.21 9.895v4.632l2.527 1.263z");
}

.ft5dv1b6b {
  fill: none;
}

.ms1h7-g1v {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 15.37v-3.58l2.948-1.894z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qhgf1-bky {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.79 9.474L5.262 8.21L12 4l6.316 3.79l-2.526 1.263L12 6.947zm8.42 5.052l2.527 1.264L12 20l-6.316-3.79l2.526-1.263L12 17.054zm-1.263-4.63H9.052L12 11.79z");
}

.rjaxoxbhu {
  fill: var(--svg-color--004f9f, #004f9f);
  d: path("M24 0H0v24h24z");
}

</style>
