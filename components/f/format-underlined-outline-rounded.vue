<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrcfxrs5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-underlined-outline-rounded" /></template>
<style>
.rrcfxrs5o {
  fill: currentColor;
  d: path("M6.192 19.25q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143h11.616q.212 0 .356.144t.144.357t-.144.356t-.356.143zm2.45-4.45q-1.217-1.258-1.217-3.415V4.39q0-.233.171-.398q.171-.166.403-.166t.395.166t.164.398v7.028q0 1.631.911 2.583q.912.952 2.531.952t2.53-.952t.912-2.583V4.391q0-.233.172-.398q.17-.166.402-.166t.396.166t.163.398v6.994q0 2.157-1.217 3.415T12 16.058T8.642 14.8");
}

</style>
