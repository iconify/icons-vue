<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="gx25r1_5p"><path class="x8r3bo3uc"/><path class="cdt9z3brp"/><path class="xyrbp57pi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-mivascript" /></template>
<style>
.cdt9z3brp {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--f7394a, #f7394a);
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M4 4h24v24H4z");
}

.gx25r1_5p {
  fill-rule: evenodd;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 1.5;
}

.x8r3bo3uc {
  fill: none;
  d: path("M0 0h32v32H0z");
}

.xyrbp57pi {
  fill: var(--svg-color--f7394a, #f7394a);
  fill-rule: nonzero;
  d: path("m21.765 13.008l-4.181 5.825a1.95 1.95 0 0 1-1.613.835q-.483 0-.904-.221a2.05 2.05 0 0 1-.708-.614l-4.205-5.825v9.13H8V9.862h1.002q.784 0 1.498.368c.714.368.871.586 1.186 1.02l4.32 6.022l4.285-6.009q.46-.664 1.181-1.033c.721-.369.984-.368 1.514-.368H24v12.276h-2.235z");
}

</style>
