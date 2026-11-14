<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="deqqgdcpu"/><path class="fjtqg9bma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:anchor-up" /></template>
<style>
.deqqgdcpu {
  d: path("M9.5 2zA1.5 1.5 0 0 1 11 3.5V5a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 8 5V3.5A1.5 1.5 0 0 1 9.5 2");
}

.fjtqg9bma {
  d: path("M7.5 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 2v9.25M6 13.25h7m-.076 5.425q-.374.26-.784.461t-.846.338q-.435.136-.886.205q-.452.069-.908.069q-.139 0-.278-.006q-.139-.007-.277-.02q-.139-.012-.277-.032q-.137-.019-.274-.045t-.272-.057q-.135-.032-.269-.07t-.266-.083t-.261-.095t-.257-.106t-.252-.119t-.245-.13q-.122-.068-.24-.141q-.118-.074-.232-.152q-.115-.079-.226-.163t-.217-.174q-.107-.089-.21-.183q-.102-.093-.2-.192t-.192-.202q-.093-.103-.182-.21q-.088-.107-.172-.218q-.083-.112-.162-.227q-.078-.115-.151-.233t-.14-.24t-.129-.247q-.061-.125-.117-.252t-.105-.257t-.094-.262q-.043-.132-.081-.266q-.037-.134-.069-.27q-.031-.135-.056-.272t-.043-.275t-.031-.276M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
