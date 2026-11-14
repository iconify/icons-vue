<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zim-pz91c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dairy-free-drink" /></template>
<style>
.zim-pz91c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.473 3.495q.105-.117.233-.21q.127-.092.271-.156t.298-.096T8.586 3h6.828q.076 0 .152.008q.076.007.151.023q.075.015.147.038q.073.023.143.053t.137.067t.129.081t.121.094q.057.05.11.105q.052.055.099.116q.046.06.087.125t.073.134q.033.068.06.14t.045.146t.03.149t.015.152q.003.076-.001.152l-.443 7.98m-.461 7.399q-.036.112-.089.218q-.054.105-.123.201q-.07.095-.153.179q-.084.084-.179.153q-.096.07-.201.123q-.106.054-.218.091q-.112.036-.229.055q-.117.018-.235.018H9.419q-.071 0-.142-.007q-.071-.006-.14-.02q-.07-.013-.139-.033q-.068-.02-.134-.046q-.066-.027-.129-.059t-.123-.071q-.06-.038-.116-.082q-.056-.043-.108-.092t-.099-.103q-.046-.053-.088-.111t-.077-.119t-.066-.126q-.03-.064-.054-.131q-.023-.067-.041-.136q-.017-.069-.027-.14q-.011-.07-.015-.141l-.454-8.171M11.95 8h4.8M3.5 3.5l17 17");
}

</style>
