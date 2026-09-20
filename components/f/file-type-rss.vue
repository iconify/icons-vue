<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGvSi4fdXe" x1="30.06" x2="225.94" y1="30.06" y2="225.94" gradientTransform="matrix(.11 0 0 .11 2 2)" gradientUnits="userSpaceOnUse"><stop offset="0" class="d9jhbabfv"/><stop offset=".11" class="py8z9pl-i"/><stop offset=".35" class="vmiobubsi"/><stop offset=".5" class="s3xnojb2b"/><stop offset=".7" class="sjj2hrpqf"/><stop offset=".89" class="zo28i8s8i"/><stop offset="1" class="wok6ixhpp"/></linearGradient></defs><rect class="h46j0cfgp"/><rect class="uopyg11om"/><rect fill="url(#SVGvSi4fdXe)" class="x1k0fsb-b"/><path class="xl6fccczb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-rss" /></template>
<style>
.d9jhbabfv {
  stop-color: var(--svg-color--e3702d, #e3702d);
}

.h46j0cfgp {
  width: 28px;
  height: 28px;
  x: 2px;
  y: 2px;
  fill: var(--svg-color--cc5d15, #cc5d15);
  rx: 6.01px;
  ry: 6.01px;
}

.py8z9pl-i {
  stop-color: var(--svg-color--ea7d31, #ea7d31);
}

.s3xnojb2b {
  stop-color: var(--svg-color--fb9e3a, #fb9e3a);
}

.sjj2hrpqf {
  stop-color: var(--svg-color--ea7c31, #ea7c31);
}

.uopyg11om {
  width: 26.91px;
  height: 26.91px;
  x: 2.54px;
  y: 2.54px;
  fill: var(--svg-color--f49c52, #f49c52);
  rx: 5.47px;
  ry: 5.47px;
}

.vmiobubsi {
  stop-color: var(--svg-color--f69537, #f69537);
}

.wok6ixhpp {
  stop-color: var(--svg-color--d95b29, #d95b29);
}

.x1k0fsb-b {
  width: 25.82px;
  height: 25.82px;
  x: 3.1px;
  y: 3.1px;
  rx: 5.14px;
  ry: 5.14px;
}

.xl6fccczb {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.82 6.16v3.83a15.31 15.31 0 0 1 15.3 15.3h3.83A19.14 19.14 0 0 0 6.81 6.17zm0 6.45v3.72a8.97 8.97 0 0 1 8.96 8.97h3.72A12.69 12.69 0 0 0 6.81 12.6zm2.62 7.44a2.63 2.63 0 0 0-2.63 2.62a2.63 2.63 0 0 0 2.63 2.63a2.63 2.63 0 0 0 2.63-2.63a2.63 2.63 0 0 0-2.63-2.63z");
}

.zo28i8s8i {
  stop-color: var(--svg-color--de642b, #de642b);
}

</style>
