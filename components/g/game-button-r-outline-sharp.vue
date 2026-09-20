<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4-0-vb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:game-button-r-outline-sharp" /></template>
<style>
.v4-0-vb2h {
  fill: currentColor;
  d: path("M9.125 15.5H10.5v-2.55h.925l1.825 2.55h1.625l-2.05-2.725q.7-.275 1.063-.8t.362-1.25q0-1.125-.7-1.675T11.5 8.5H9.125zm1.375-3.575v-2.2l.925-.025q.65-.025 1.025.275t.375.825q0 .55-.412.838t-1.188.287zM2 20V8q0-1.65 1.175-2.825T6 4h12q1.65 0 2.825 1.175T22 8v12zm2-2h16V8q0-.825-.587-1.412T18 6H6q-.825 0-1.412.588T4 8zm0 0h16z");
}

</style>
