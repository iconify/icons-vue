<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ia2fmb0_f"/><path class="ln087ybbc"/><path class="tms3vccny"/><path class="uc5n3ybcz"/><path class="imq7sxbhw"/><path class="ncntbpb7p"/><path class="uxi1ps7yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-bazel-ignore" /></template>
<style>
.ia2fmb0_f {
  fill: var(--svg-color--76d275, #76d275);
  d: path("m9 2l7 7l-7 7l-7-7z");
}

.imq7sxbhw {
  fill: var(--svg-color--00701a, #00701a);
  d: path("M16 23v7l-7-7v-7z");
}

.ln087ybbc {
  fill: var(--svg-color--43a047, #43a047);
  d: path("M2 9v7l7 7v-7z");
}

.ncntbpb7p {
  fill: var(--svg-color--004300, #004300);
  d: path("m16 23l7-7v7l-7 7z");
}

.tms3vccny {
  fill: var(--svg-color--76d275, #76d275);
  d: path("m23 2l7 7l-7 7l-7-7z");
}

.uc5n3ybcz {
  fill: var(--svg-color--43a047, #43a047);
  d: path("M30 9v7l-7 7v-7zM16 9l7 7l-7 7l-7-7z");
}

.uxi1ps7yl {
  fill: var(--svg-color--ff0027, #ff0027);
  d: path("M9 2L2 9v7l14 14l14-14V9l-7-7l-7 7z");
}

</style>
