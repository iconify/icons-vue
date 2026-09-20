<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a7xw2r38h"/><path class="u-o9e9bpq"/><path class="n4dugw98a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-hypr" /></template>
<style>
.a7xw2r38h {
  fill: var(--svg-color--656868, #656868);
  d: path("M2 29.99h27.91L8.7 8.52l-4.48 8.53z");
}

.n4dugw98a {
  fill: var(--svg-color--ffce01, #ffce01);
  d: path("M2 13.18L13.19 2H30L2 29.99z");
}

.u-o9e9bpq {
  fill: var(--svg-color--2b2b2b, #2b2b2b);
  d: path("m2 30l17.34-10.72l-3.3-3.34z");
}

</style>
