<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="hrf_cfbnw"/><path class="kekssmb5o"/><path class="d0ku6rbcb"/><circle class="zet2abb5h"/><circle class="qsxne3nct"/><circle class="v2_ro7_-i"/><circle class="je35y3bgh"/><path class="mxhd2k0pj"/><path class="ij_32rgav"/><path class="wm23c1bgj"/><path class="rux3q_b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:beverage-box" /></template>
<style>
.d0ku6rbcb {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M25 36H10a1 1 0 0 1-1-1V10.454S9.448 10 10 10h15c.552 0 1 .454 1 .454V35a1 1 0 0 1-1 1");
}

.hrf_cfbnw {
  fill: var(--svg-color--e3a919, #e3a919);
  d: path("m28.337 32.563l-2.579 3.082c-.552.553-1.758.007-1.758-.545V12.001c0-.552 2.372-4.501 5-4.501l-.028 23.007c0 1.134-.093 1.308-.635 2.056");
}

.ij_32rgav {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M25.434.44c-1.124-.446-2.082-.451-2.853-.01c-.791.454-1.287 1.314-1.484 2.562l1.975.367c.108-.664.322-.989.52-1.103c.22-.129.63-.105 1.146.082z");
}

.je35y3bgh {
  cx: 19.5px;
  cy: 23.5px;
  r: 2.5px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.kekssmb5o {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M26 10.454H9l.194-.348L12.74 7.5c.486-.379.831-.5 1.383-.5h14.363c.188 0 .514.277.344.47z");
}

.mxhd2k0pj {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M22.999 8.464s-.21.431-.967.431s-1.033-.431-1.033-.431V4.342c0-1.993.532-3.309 1.582-3.911c1.005-.576 2.326-.398 3.922.535c1.274.743 4.421 2.972 4.496 3.034c0 0 .165.565-.303 1.1s-.965.447-.965.447c-.018-.014-3.101-2.191-4.236-2.855c-.881-.515-1.584-.623-1.904-.436c-.279.16-.592.726-.592 2.086z");
}

.qsxne3nct {
  cx: 15px;
  cy: 21px;
  r: 4px;
  fill: var(--svg-color--ea596e, #ea596e);
}

.rux3q_b8u {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("m28.908 7.796l-2.536 3.036c-.163.201-.471.223-.684.05s-.255-.479-.093-.68l2.536-3.036c.163-.201.471-.223.684-.05c.214.174.255.479.093.68");
}

.v2_ro7_-i {
  cx: 19.5px;
  cy: 23.5px;
  r: 4.5px;
  fill: var(--svg-color--ffe8b6, #ffe8b6);
}

.wm23c1bgj {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M25.931 11H9.5c-.275 0-.5-.225-.5-.5s.225-.5.5-.5h16.431c.275 0 .5.225.5.5s-.225.5-.5.5");
}

.zet2abb5h {
  cx: 15px;
  cy: 27px;
  r: 3px;
  fill: var(--svg-color--f4900c, #f4900c);
}

</style>
