<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiowwabpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bia-outline-rounded" /></template>
<style>
.yiowwabpa {
  fill: currentColor;
  d: path("M6 18v-2q0-.425.288-.712T7 15t.713.288T8 16v2h2v-2q0-.425.288-.712T11 15t.713.288T12 16v2h2v-2q0-.425.288-.712T15 15t.713.288T16 16v2h4v-6.925q-.825.475-1.862.7T16 12q-1.125 0-2.2-.25T11.875 11H4v7zm1-9h3.15q-.075-.225-.112-.475T10 8t.038-.525T10.15 7H7zm11.725.625Q20 9.25 20 8t-1.275-1.625T16 6t-2.725.375T12 8t1.275 1.625T16 10t2.725-.375M4 20q-.825 0-1.412-.587T2 18v-7q0-.825.588-1.412T4 9h1V7q0-.825.588-1.412T7 5h4.875q.85-.5 1.925-.75T16 4q2.275 0 4.138.988T22 8v10q0 .825-.587 1.413T20 20zm2-2h14H4z");
}

</style>
