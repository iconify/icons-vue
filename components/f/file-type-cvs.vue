<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gmcsn4b_u"/><circle class="i6riehb3u"/><path class="ukvflgenn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-cvs" /></template>
<style>
.gmcsn4b_u {
  fill: var(--svg-color--f90, #f90);
  d: path("M21.74 12.734A7.64 7.64 0 0 1 27.134 8.4a8.2 8.2 0 0 1 2.747-.129a5.8 5.8 0 0 1 .071 1.917c-.5 3.81-4.748 5.758-5.305 6c.971.562 4.273 2.624 4.631 5.995a5.7 5.7 0 0 1 .007 1.125a5 5 0 0 1-.817.228c-3.167.6-6.026-2.119-6.862-2.971a15.2 15.2 0 0 1-5.56 2.741c-5.77 1.475-10.947-.913-10.9-1.227c.015-.1.55-.014 1.715-.339a5.8 5.8 0 0 0 1.468-.595a2.46 2.46 0 0 0 1.124-1.1a1.8 1.8 0 0 0 .123-.458a7.3 7.3 0 0 1-2.9 1.265a9 9 0 0 1-1.421.124a2.5 2.5 0 0 1-.856-.076a2.4 2.4 0 0 1-.517-.221a3.6 3.6 0 0 1-.837-.635a3.4 3.4 0 0 1-.883-1.356a3.15 3.15 0 0 1-.085-1.689a9 9 0 0 1 .451-1.458a9 9 0 0 1 2.11-3.089a10.4 10.4 0 0 1 3.388-2.461a10.6 10.6 0 0 1 4.493-.924a12.6 12.6 0 0 1 5.094 1.123a15.1 15.1 0 0 1 4.127 2.544");
}

.i6riehb3u {
  cx: 6.903px;
  cy: 15.055px;
  r: 1.907px;
  fill: var(--svg-color--099, #099);
}

.ukvflgenn {
  fill: var(--svg-color--67cbca, #67cbca);
  d: path("M7.281 15.794a.948.948 0 0 1-.926-1.229a1 1 0 0 1 .206-.379a.3.3 0 0 1 .488.07l.03.064a.24.24 0 0 1-.041.263a.4.4 0 0 0-.088.157a.34.34 0 0 0 .03.277a.37.37 0 0 0 .366.15a.24.24 0 0 1 .244.11l.038.062a.3.3 0 0 1-.206.446a1 1 0 0 1-.141.009");
}

</style>
