<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aoo8zjjko"/><path class="cmm0iy9lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-reason" /></template>
<style>
.aoo8zjjko {
  fill: var(--svg-color--dd4b39, #dd4b39);
  d: path("M2 2h28v28H2z");
}

.cmm0iy9lf {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.051 17.527h5.072a4.95 4.95 0 0 1 2.977.973a3.3 3.3 0 0 1 1.128 2.267a4.12 4.12 0 0 1-.778 3.022a3.6 3.6 0 0 1-1.137.905l2.247 3.549h-3.061l-1.6-3.043h-2.154v3.032H9.051zm2.69 2.128v3.438h1.989a2.18 2.18 0 0 0 1.468-.452a1.81 1.81 0 0 0 .482-1.544a1.47 1.47 0 0 0-.705-1.18a2.77 2.77 0 0 0-1.437-.269c-.598.006-1.797.007-1.797.007m8.384-2.13h8.35v2.13h-5.66V21.8h5.11v2.119H22.82V26.1h5.824v2.142h-8.519z");
}

</style>
