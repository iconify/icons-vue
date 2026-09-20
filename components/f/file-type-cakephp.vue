<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b_s7_cc-q"/><path class="e6tj0mk7a"/><path class="rbi-ys25w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-cakephp" /></template>
<style>
.b_s7_cc-q {
  fill: var(--svg-color--d33e44, #d33e44);
  d: path("m16 13.819l10.949 2.719C28.855 15.792 30 14.846 30 13.819V9.445c0-2.409-6.27-4.369-14-4.369S2 7.035 2 9.445v4.375c0 2.411 6.267 4.369 14 4.369z");
}

.e6tj0mk7a {
  fill: var(--svg-color--fff, #fff);
  d: path("M26.948 16.538L16 13.818v4.37l10.949 2.72C28.854 20.16 30 19.216 30 18.188v-4.37c0 1.028-1.146 1.973-3.052 2.72M2 13.818v4.37c0 2.411 6.267 4.366 14 4.366v-4.366c-7.733 0-14-1.96-14-4.37");
}

.rbi-ys25w {
  fill: var(--svg-color--d33e44, #d33e44);
  d: path("M26.948 20.908L16 18.188v4.37l10.949 2.72c1.905-.747 3.051-1.692 3.051-2.72v-4.37c0 1.028-1.146 1.973-3.052 2.72M2 18.188v4.37c0 2.411 6.267 4.366 14 4.366v-4.366c-7.733 0-14-1.958-14-4.37");
}

</style>
