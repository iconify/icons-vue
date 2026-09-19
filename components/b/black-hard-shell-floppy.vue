<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="e2_ssi4xv"/><path class="kmpk-zboc"/><path class="ub3_zghci"/><path class="rme1cmbwo"/><circle class="cfd_qcbim"/><circle class="gt1pps2rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:black-hard-shell-floppy" /></template>
<style>
.cfd_qcbim {
  cx: 31.852px;
  cy: 27.502px;
  r: 9.793px;
  fill: var(--svg-color--e7e6e6, #e7e6e6);
}

.e2_ssi4xv {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M62.823 63.13H.883a.945.945 0 0 1-.934-.937V1.945c0-.51.424-.938.934-.938h61.942c.279 0 .49.104.637.25c.011.011.015.018.021.024a.87.87 0 0 1 .275.664v60.246a.945.945 0 0 1-.933.937");
}

.gt1pps2rg {
  cx: 31.75px;
  cy: 27.5px;
  r: 3.531px;
  fill: var(--svg-color--25333a, #25333a);
}

.kmpk-zboc {
  fill: var(--svg-color--3f565f, #3f565f);
  d: path("M60.53 63.13H2.969c-.47 0-.867-.41-.867-.903V3.844c0-.499.397-.905.867-.905h57.569a.83.83 0 0 1 .608.255c.012.021.022.024.029.031c.14.14.232.349.232.619v58.379c0 .493-.399.903-.869.903");
}

.rme1cmbwo {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M44.21 59.803H33.547c-.089 0-.164-.108-.164-.237V44.261c0-.127.075-.238.164-.238H44.21c.049 0 .085.025.113.064l.002.005l.005.009a.3.3 0 0 1 .047.16v15.305c0 .128-.078.237-.167.237");
}

.ub3_zghci {
  fill: var(--svg-color--e7e6e6, #e7e6e6);
  d: path("M50.871 63.13H12.832c-.315 0-.577-.155-.577-.337V41.04c0-.185.262-.338.577-.338h38.039a.75.75 0 0 1 .423.112c.093.051.155.129.155.227v21.753c-.001.181-.262.336-.578.336");
}

</style>
