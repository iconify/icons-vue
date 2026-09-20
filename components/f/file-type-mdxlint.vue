<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="d6qrl9arh"/><path class="jhulqslhm"/><path class="q6u_t9ygg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-mdxlint" /></template>
<style>
.d6qrl9arh {
  width: 28px;
  height: 11.4px;
  x: 2px;
  y: 10.3px;
  fill: var(--svg-color--f9ac00, #f9ac00);
  rx: 0.923px;
}

.jhulqslhm {
  fill: none;
  stroke: var(--svg-color--000, #000);
  stroke-width: var(--svg-stroke-width--1-23px, 1.23px);
  d: path("m27 18.6l-6-6m.051 6l6-6zm-15.8.564v-5.13l2.82 2.82l2.87-2.87v5.13m5.38-.769v-6zm-2.77-2.62l2.77 2.77l2.77-2.77");
}

.q6u_t9ygg {
  fill: none;
  stroke: var(--svg-color--d00, #d00);
  stroke-width: var(--svg-stroke-width--0-41px, 0.41px);
  d: path("m4.31 19.8l.615.615l.615-.615l.615.615l.615-.615l.615.615L8 19.8l.615.615l.615-.615l.615.615l.615-.615l.615.615l.615-.615l.615.615l.615-.615l.615.615l.615-.615l.615.615l.615-.615l.615.615l.615-.615l.615.615l.615-.615l.615.615l.615-.615l.615.615l.615-.615l.615.615l.615-.615l.615.615l.615-.615l.615.615l.615-.615l.615.615l.615-.615l.615.615l.615-.615l.615.615l.615-.615");
}

</style>
