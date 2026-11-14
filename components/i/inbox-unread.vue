<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w-wex2bir"/><path class="xs03ubb6l"/><path class="yc8b1qb1r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:inbox-unread" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w-wex2bir {
  d: path("M13.566 20H5q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182q-.077-.095-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238q-.024-.121-.036-.243T2.5 17.5v-5L5 5.25q.041-.139.105-.269q.064-.131.148-.249t.187-.221q.102-.102.22-.187q.118-.084.249-.148q.13-.063.269-.105t.283-.059q.144-.018.289-.012h10.5q.145-.006.289.012t.283.059t.269.105t.249.148q.118.085.22.187q.103.103.187.221t.148.249t.105.269l2.5 7.25v1.561");
}

.xs03ubb6l {
  d: path("M2.5 12.5h5L9 15h6l1.5-2.5h5");
}

.yc8b1qb1r {
  fill: currentColor;
  d: path("M16.25 19a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

</style>
