<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="e416p-cfv"/><path class="ddkx7ebhg"/><circle class="hqs7ndbxp"/><circle class="j2i6zyyyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:cherries" /></template>
<style>
.ddkx7ebhg {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M26.547 8.818c-3.476.96-5.051 2.546-10.749.667c-4.72-1.557-7.037-4.207-6.345-6.305s3.18-3.163 7.9-1.606c4.749 1.567 4.123 3.466 9.194 7.244");
}

.e416p-cfv {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M25.999 24a1 1 0 0 1-.572-.181C18.884 19.239 13.261 11.453 10.03 6.38c1.699 10.528.997 16.458.962 16.744a1 1 0 0 1-1.984-.247c.009-.079.936-8.033-1.986-21.668a1 1 0 0 1 1.86-.68c.079.148 8.007 14.873 17.691 21.652A1 1 0 0 1 25.999 24");
}

.hqs7ndbxp {
  cx: 26px;
  cy: 28px;
  r: 8px;
  fill: var(--svg-color--be1931, #be1931);
}

.j2i6zyyyg {
  cx: 11px;
  cy: 28px;
  r: 8px;
  fill: var(--svg-color--be1931, #be1931);
}

</style>
