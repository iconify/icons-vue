<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<ellipse class="el1gr3ksm"/><path class="ar3if1byq"/><circle class="kdnhh-bnd"/><circle class="bido1acce"/><circle class="kfe-12bma"/><ellipse class="rhn-lc5wp"/><path class="k89qbcbxd"/><circle class="up5e3brat"/><circle class="jqfij84dy"/><circle class="w-on30b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:eyes" /></template>
<style>
.ar3if1byq {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M8.828 32.031C3.948 32.031.125 25.868.125 18S3.948 3.969 8.828 3.969S17.531 10.132 17.531 18s-3.823 14.031-8.703 14.031m0-26.562C4.856 5.469 1.625 11.09 1.625 18s3.231 12.531 7.203 12.531S16.031 24.91 16.031 18S12.8 5.469 8.828 5.469");
}

.bido1acce {
  cx: 6.594px;
  cy: 18px;
  r: 3.565px;
  fill: var(--svg-color--292f33, #292f33);
}

.el1gr3ksm {
  cx: 8.828px;
  cy: 18px;
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  rx: 7.953px;
  ry: 13.281px;
}

.jqfij84dy {
  cx: 25px;
  cy: 18px;
  r: 3.565px;
  fill: var(--svg-color--292f33, #292f33);
}

.k89qbcbxd {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M27.234 32.031c-4.88 0-8.703-6.163-8.703-14.031s3.823-14.031 8.703-14.031S35.938 10.132 35.938 18s-3.824 14.031-8.704 14.031m0-26.562c-3.972 0-7.203 5.622-7.203 12.531s3.231 12.531 7.203 12.531S34.438 24.91 34.438 18S31.206 5.469 27.234 5.469");
}

.kdnhh-bnd {
  cx: 6.594px;
  cy: 18px;
  r: 4.96px;
  fill: var(--svg-color--8899a6, #8899a6);
}

.kfe-12bma {
  cx: 7.911px;
  cy: 15.443px;
  r: 1.426px;
  fill: var(--svg-color--f5f8fa, #f5f8fa);
}

.rhn-lc5wp {
  cx: 27.234px;
  cy: 18px;
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  rx: 7.953px;
  ry: 13.281px;
}

.up5e3brat {
  cx: 25px;
  cy: 18px;
  r: 4.96px;
  fill: var(--svg-color--8899a6, #8899a6);
}

.w-on30b1g {
  cx: 26.317px;
  cy: 15.443px;
  r: 1.426px;
  fill: var(--svg-color--f5f8fa, #f5f8fa);
}

</style>
