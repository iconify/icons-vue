<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="buq4ssbjv"><ellipse class="xlgw1_b-l"/><path class="gekl-yb7s"/><path class="c8yintbrl"/></g><ellipse class="is260jb_p"/><ellipse class="jgla3bcch"/><path class="nf3qc29lb"/><path class="fx6k4ywys"/><circle class="aqqar33eo"/><path class="dfz0g635z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:cocktail-glass" /></template>
<style>
.aqqar33eo {
  cx: 38.98px;
  cy: 17.632px;
  r: 2.848px;
  fill: var(--svg-color--ee4237, #ee4237);
}

.buq4ssbjv {
  fill: var(--svg-color--bac4c9, #bac4c9);
  fill-opacity: var(--svg-fill-opacity--0-627, 0.627);
}

.c8yintbrl {
  d: path("M33.33 13.08h21.78L44.22 25.514L33.33 37.943L22.446 25.514L11.554 13.08z");
  opacity: var(--svg-opacity--0-67, 0.67);
}

.dfz0g635z {
  fill: var(--svg-color--f79420, #f79420);
  d: path("M33.442 15.04H52.19l-9.377 10.708l-9.371 10.698l-9.372-10.698l-9.375-10.708z");
  opacity: var(--svg-opacity--0-36, 0.36);
}

.fx6k4ywys {
  fill: var(--svg-color--2bb573, #2bb573);
  d: path("M46.45 18.202a5.573 5.573 0 0 1-11.147 0a5.574 5.574 0 1 1 11.147 0");
}

.gekl-yb7s {
  d: path("M34.745 58.24c0 .719-.582 1.308-1.306 1.308a1.31 1.31 0 0 1-1.305-1.308V33.02a1.307 1.307 0 1 1 2.611 0z");
  opacity: var(--svg-opacity--0-67, 0.67);
}

.is260jb_p {
  cx: 33.33px;
  cy: 13.08px;
  fill: var(--svg-color--93b5cc, #93b5cc);
  rx: 21.779px;
  ry: 3.42px;
}

.jgla3bcch {
  cx: 33.33px;
  cy: 13.641px;
  fill: var(--svg-color--f79420, #f79420);
  rx: 18.209px;
  ry: 2.859px;
}

.nf3qc29lb {
  fill: var(--svg-color--e7e6e6, #e7e6e6);
  d: path("M29.25 30.416a.593.593 0 1 1-.838-.839L56.758 1.229a.59.59 0 0 1 .838 0a.59.59 0 0 1 0 .838z");
}

.xlgw1_b-l {
  cx: 33.33px;
  cy: 59.55px;
  opacity: var(--svg-opacity--0-67, 0.67);
  rx: 15.08px;
  ry: 4.058px;
}

</style>
