<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="t_2lkqbxb"><g class="xsfz_db_a"><path class="s5bk0bcku"/><path class="s3mipef2v"/></g><path class="ov2_iib0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-platformatic" /></template>
<style>
.ov2_iib0r {
  stroke: var(--svg-color--000, #000);
  stroke-width: var(--svg-stroke-width--1-05px, 1.05px);
  d: path("m27.3 14.47l2.18 1.29v1.29l-2.18 1.29M4.96 11.4l-2.44 1.42v6.3l2.39 1.38m4.43 1.26v1.4l3.57 1.98l2.74-1.6l-.02-2.93m2.7-1.64v1.54l2.57 1.51l3.76-2.25v-6.13l-3.7-2.13");
}

.s3mipef2v {
  d: path("M9.34 19.15v-1.98l1.76-1.07");
}

.s5bk0bcku {
  d: path("M7.57 18.06v4.52m1.77-5.41l3.6 2.09l5.36-3.11V9.93l-5.37-3.1l-5.36 3.1v5.4");
}

.t_2lkqbxb {
  fill: none;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xsfz_db_a {
  stroke: var(--svg-color--21fa90, #21fa90);
  stroke-width: var(--svg-stroke-width--0-98px, 0.98px);
}

</style>
