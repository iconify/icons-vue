<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="bhp35pb_e"/><path class="yb4gu8k6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-slice" /></template>
<style>
.bhp35pb_e {
  cx: 16px;
  cy: 16px;
  r: 14px;
  fill: var(--svg-color--447cd2, #447cd2);
}

.yb4gu8k6n {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.821 13.321a2.7 2.7 0 0 1-1.714.536a2.9 2.9 0 0 1-2.18-.9a4.14 4.14 0 0 1-.807-2.938a3.88 3.88 0 0 1 .89-2.794a3 3 0 0 1 2.237-.842a2.86 2.86 0 0 1 1.682.506a2.27 2.27 0 0 1 .9 1.342l2.483-.493a14 14 0 0 0-2.881-2.924a6.9 6.9 0 0 0-2.033-.3a5.86 5.86 0 0 0-4.2 1.453a5.5 5.5 0 0 0-1.643 4.188a5.24 5.24 0 0 0 1.534 4.052a5.7 5.7 0 0 0 4.024 1.52A5.8 5.8 0 0 0 25.4 14.9a4.74 4.74 0 0 0 1.881-2.617l-2.409-.7a3.13 3.13 0 0 1-1.051 1.738");
}

</style>
