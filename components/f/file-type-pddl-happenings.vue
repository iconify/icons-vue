<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ap3ncmtqc"/><ellipse class="x_dt3hxzl"/><path class="qizu3hoqv"/><ellipse class="rz3jfvt9q"/><path class="vjxa1139p"/><ellipse class="lxb41v97o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-pddl-happenings" /></template>
<style>
.ap3ncmtqc {
  fill: var(--svg-color--0055d4, #0055d4);
  d: path("M11.36 4.15h17.37v6.45H11.36z");
}

.lxb41v97o {
  cx: 5.936px;
  cy: 24.964px;
  fill: var(--svg-color--0055d4, #0055d4);
  rx: 2.638px;
  ry: 2.785px;
}

.qizu3hoqv {
  fill: var(--svg-color--0055d4, #0055d4);
  d: path("M11.433 12.945h17.37v6.45h-17.37z");
}

.rz3jfvt9q {
  cx: 5.936px;
  cy: 16.169px;
  fill: var(--svg-color--0055d4, #0055d4);
  rx: 2.638px;
  ry: 2.785px;
}

.vjxa1139p {
  fill: var(--svg-color--0055d4, #0055d4);
  d: path("M11.433 21.739h17.37v6.45h-17.37z");
}

.x_dt3hxzl {
  cx: 5.863px;
  cy: 7.375px;
  fill: var(--svg-color--0055d4, #0055d4);
  rx: 2.638px;
  ry: 2.785px;
}

</style>
