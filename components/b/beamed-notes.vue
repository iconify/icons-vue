<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csy77xb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:beamed-notes" /></template>
<style>
.csy77xb6k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 16.031V4.5q0-.065.011-.128q.011-.064.033-.124q.022-.061.053-.117q.032-.057.073-.106q.041-.05.09-.093t.104-.075t.115-.056t.124-.036l10-2q.072-.015.146-.015t.147.014t.14.043t.13.069t.114.093t.093.114t.07.129t.042.141t.015.147v14q0 3-3.5 3t-3.5-3t3.5-3q1.209 0 2 .358V3.415l-8.5 1.7V18.5q0 1.287-1.081 2.171Q8.407 21.5 7 21.5q-3.5 0-3.5-3t3.5-3q1.126 0 2 .531");
}

</style>
