<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":600};
const content = `<path class="xdhw55bqw"/><path class="ogcr15bsd"/><path class="los275b7v"/><path class="pfpt_xbzl"/><path class="sai-a0bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-wgsl" /></template>
<style>
.los275b7v {
  fill: var(--svg-color--0076cc, #0076cc);
  fill-rule: evenodd;
  d: path("m534.628 507.5l-120.5-208h241z");
}

.ogcr15bsd {
  fill: var(--svg-color--0066b0, #0066b0);
  fill-rule: evenodd;
  d: path("m534.628 91.5l-120.5 208h241z");
}

.pfpt_xbzl {
  fill: var(--svg-color--0086e8, #0086e8);
  fill-rule: evenodd;
  d: path("m654.628 300.5l-60.5-104h121z");
}

.sai-a0bsa {
  fill: var(--svg-color--0093ff, #0093ff);
  fill-rule: evenodd;
  d: path("m654.628 92.5l-60.5 104h121z");
}

.xdhw55bqw {
  fill: var(--svg-color--005a9c, #005a9c);
  fill-rule: evenodd;
  d: path("M293.628 508.5L52.873 91.5h481.51z");
}

</style>
