<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><clipPath id="SVGbYWPmdhr"><use href="#SVGBgtDsecu"/></clipPath><path id="SVGBgtDsecu" class="jd4miep3w"/></defs><path class="nifx3652v"/><use href="#SVGBgtDsecu"/><g clip-path="url(#SVGbYWPmdhr)"><path class="dsxc3bc6v"/><path class="rg_jspblb"/></g><circle class="f4xkjac0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-rego" /></template>
<style>
.dsxc3bc6v {
  fill: var(--svg-color--536367, #536367);
  d: path("M16.053 7.962h9.549v21.899h-9.549z");
}

.f4xkjac0s {
  cx: 16.04px;
  cy: 16.241px;
  r: 1.166px;
  fill: var(--svg-color--fff, #fff);
}

.jd4miep3w {
  fill: none;
  d: path("M7.055 16.241c3.415-10.22 14.759-9.473 17.924 0l.1 5.893a15.56 15.56 0 0 0-9.036 7.246a17.64 17.64 0 0 0-9.013-7.034Z");
}

.nifx3652v {
  fill: var(--svg-color--bfbfbf, #bfbfbf);
  fill-rule: evenodd;
  d: path("m7.03 16.241l2.6-4.559c-2.418-.312-2.606-3.431-.8-9.062c-5.021 6.233-6.41 7.608-1.8 13.621m17.94 0l-2.595-4.559c2.418-.312 2.606-3.431.8-9.062c5.016 6.233 6.405 7.608 1.795 13.621");
}

.rg_jspblb {
  fill: var(--svg-color--78929a, #78929a);
  d: path("M5.322 7.962h10.732v21.899H5.322z");
}

</style>
