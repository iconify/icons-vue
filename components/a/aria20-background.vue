<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gl0o3sbjw"/><path class="i7l9ae-iv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aria20-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gl0o3sbjw {
  fill: var(--svg-color--b99247, #b99247);
  d: path("M24 0H0v24h24z");
}

.i7l9ae-iv {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.121 8.134c.59-.685 1.507-1.728 3.891-1.728c2.28 0 2.644 1.496 2.644 2.004v.17c.01.586.022 1.524-.624 1.833c-.695.331-1.545.552-2.417.773c-2.5.635-5.21 1.325-5.238 4.967a2.485 2.485 0 0 1 2.533 3.505c.59.215 1.325.342 2.219.342c.856 0 2.605-.47 3.527-2.208c.165.723.927 2.208 2.76 2.208s3.046-.497 3.31-.745v-.734h-.54c-.414-.006-1.667-.293-1.667-1.38V8.465c0-1.474-.452-4.305-4.967-4.465c-1.27 0-3.869.414-6.071 2.208l.414 1.931h.226zm6.535 3.587v3.632c-.055.817-.552 2.44-2.114 2.44s-1.81-1.502-1.739-2.252c-.055-.735.221-2.346 1.739-2.937q1.081-.383 2.114-.883M5.653 20a1.38 1.38 0 1 0 0-2.76a1.38 1.38 0 0 0 0 2.76");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
