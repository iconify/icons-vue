<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jjujl6-po"/><path class="b5os5urue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:first-class-carriage" /></template>
<style>
.b5os5urue {
  d: path("M5.25 7.5h3v3h-3Zm5.25 0h3v3h-3Zm5.25 0h3v3h-3ZM4 16.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8.563-1.058q-.104-.105-.227-.188q-.123-.082-.26-.139t-.282-.086Q11.648 15 11.5 15q-.074 0-.147.007t-.146.022q-.072.014-.142.036q-.071.021-.139.049t-.133.063t-.126.076q-.062.041-.119.087q-.057.047-.109.099t-.099.109q-.046.057-.087.119t-.076.126t-.063.133t-.049.139q-.022.07-.036.142q-.015.073-.022.146T10 16.5t.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022T11.5 18q.243 0 .474-.077t.426-.223m5.864-2.658l.166.335a1.5 1.5 0 0 0 1.129.821l.37.053a.574.574 0 0 1 .318.979l-.268.26a1.5 1.5 0 0 0-.431 1.328l.063.368a.574.574 0 0 1-.832.605l-.331-.174a1.5 1.5 0 0 0-1.396 0l-.331.174a.574.574 0 0 1-.832-.605l.063-.368a1.5 1.5 0 0 0-.431-1.328l-.268-.26a.574.574 0 0 1 .318-.979l.37-.053a1.5 1.5 0 0 0 1.129-.821l.166-.335a.574.574 0 0 1 1.028 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jjujl6-po {
  d: path("M12.826 15H2.5V7C2.5 5.5 4 4.5 6 4.5h12c2 0 3.5 1 3.5 2.5v6.874");
}

</style>
