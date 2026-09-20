<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xjldibcjr"/><path class="gcs1m0bdk"/><path class="sf7o9wbqk"/><path class="jnseub-pu"/><path class="gkv2wd-ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-notebooks" /></template>
<style>
.gcs1m0bdk {
  fill: var(--svg-color--767677, #767677);
  d: path("M30.809 9.233a1.383 1.383 0 1 1-1.44-1.3a1.367 1.367 0 0 1 1.44 1.297z");
}

.gkv2wd-ci {
  fill: var(--svg-color--616262, #616262);
  d: path("M14.589 12.112a1.003 1.003 0 1 1 .975-1.044a1.016 1.016 0 0 1-.975 1.044");
}

.jnseub-pu {
  fill: var(--svg-color--9e9e9e, #9e9e9e);
  d: path("M17.686 29a1.726 1.726 0 1 1-.164-.654a1.7 1.7 0 0 1 .164.655");
}

.sf7o9wbqk {
  fill: var(--svg-color--f37726, #f37726);
  d: path("M22.74 25.213c-3.673 0-6.9-1.318-8.569-3.265a9.136 9.136 0 0 0 17.138 0c-1.665 1.946-4.88 3.265-8.569 3.265m0-12.657c3.673 0 6.9 1.318 8.57 3.264a9.136 9.136 0 0 0-17.139 0c1.67-1.95 4.88-3.264 8.57-3.264");
}

.xjldibcjr {
  fill: var(--svg-color--a5a5a5, #a5a5a5);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21zm0 4.2h-8.2l1.1-2.1h7.1z");
}

</style>
