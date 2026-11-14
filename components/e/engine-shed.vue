<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o183y-urt"/><path class="u-x8jubam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:engine-shed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o183y-urt {
  d: path("M12.998 21H4.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058t-.155-.074q-.076-.04-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172v-8.366q0-.206.048-.406q.047-.2.14-.383q.093-.184.226-.341q.132-.157.298-.279l7.75-5.71q.112-.083.236-.146q.123-.064.256-.108q.132-.043.269-.065q.138-.022.277-.022t.277.022t.269.065q.133.044.256.108q.124.063.236.146l7.75 5.71q.166.122.298.279q.133.157.226.341q.093.183.14.383t.048.406v1.093");
}

.u-x8jubam {
  d: path("M5.5 21v-8h7v3.8m0 1.9V21m5.375-6.75h1.25a2.625 2.625 0 0 1 2.625 2.625v1.75a2.625 2.625 0 0 1-2.625 2.625h-1.25a2.625 2.625 0 0 1-2.625-2.625v-1.75a2.625 2.625 0 0 1 2.625-2.625M15.25 17.5h6.5");
}

</style>
