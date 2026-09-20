<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t27zdw5is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:desktop-cloud-outline-sharp" /></template>
<style>
.t27zdw5is {
  fill: currentColor;
  d: path("M9 14h6.5q1.05 0 1.775-.737T18 11.474T17.25 9.7t-1.8-.725q-.2-1.275-1.175-2.125T12 6q-1.025 0-1.875.55T8.85 8.025q-1.2.05-2.025.913T6 11q0 1.25.875 2.125T9 14m0-2q-.425 0-.712-.288T8 11t.288-.712T9 10h1.25v-.25q0-.725.513-1.237T12 8t1.238.513t.512 1.237V11h1.75q.2 0 .35.15t.15.35t-.15.35t-.35.15zm-1 9v-2h2v-2H2V3h20v14h-8v2h2v2zm-4-6h16V5H4zm0 0V5z");
}

</style>
