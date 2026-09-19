<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nt5nzci1q"/><path class="egfq1ifjv"/><path class="rzw763b0p"/><path class="tb021mmpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-ghana" /></template>
<style>
.egfq1ifjv {
  fill: var(--svg-color--699635, #699635);
  d: path("M32 62c13.1 0 24.2-8.3 28.3-20H3.7C7.8 53.7 18.9 62 32 62");
}

.nt5nzci1q {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M32 2C18.9 2 7.8 10.3 3.7 22h56.6C56.2 10.3 45.1 2 32 2");
}

.rzw763b0p {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M3.7 22C2.6 25.1 2 28.5 2 32s.6 6.9 1.7 10h56.6c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10z");
}

.tb021mmpb {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("m32 37.3l6.2 4.7l-2.4-7.6l6.2-4.9h-7.6L32 22l-2.3 7.5H22l6.2 4.9l-2.4 7.6z");
}

</style>
