<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut9e6v8zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drink-temperature" /></template>
<style>
.ut9e6v8zl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.469 20H6.414q-.071 0-.142-.007q-.07-.006-.14-.02q-.069-.013-.138-.033q-.068-.02-.134-.046q-.065-.026-.129-.058q-.063-.033-.123-.071q-.059-.038-.115-.082q-.056-.043-.108-.092q-.051-.048-.098-.102t-.088-.111t-.078-.118t-.066-.126q-.03-.064-.054-.131q-.023-.067-.041-.135q-.017-.069-.028-.139t-.015-.141l-.824-14q-.004-.076-.001-.153q.003-.076.014-.152q.011-.075.03-.15q.019-.074.045-.146q.026-.071.059-.14t.074-.134t.086-.126q.047-.061.099-.116t.111-.106q.057-.05.12-.094t.13-.081q.066-.037.137-.067q.07-.031.143-.054t.147-.038t.151-.023T5.591 3h11.818q.076 0 .153.008q.076.007.151.023q.074.015.147.038t.143.054q.071.03.137.067t.13.081q.063.044.12.094q.058.05.111.106q.052.055.099.116q.046.061.086.126q.041.065.074.134t.059.14t.045.146t.03.15t.014.152t-.001.153l-.358 6.088M4.25 7h14.5M17 18v-3.25a1.25 1.25 0 0 1 2.5 0V18a2 2 0 1 1-2.5 0");
}

</style>
