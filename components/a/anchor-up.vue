<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="av43htn8c"/><path class="vrauknjue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anchor-up" /></template>
<style>
.av43htn8c {
  d: path("M8 2h3v4.5H8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vrauknjue {
  d: path("M7.5 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 2v9.25M6 13.25h7m-.164 5.485q-.368.246-.768.436q-.401.19-.825.318q-.424.129-.862.194t-.881.065q-.139 0-.278-.006q-.139-.007-.277-.02q-.139-.012-.277-.032q-.137-.019-.274-.045t-.272-.057q-.135-.032-.269-.07t-.266-.083t-.261-.095t-.257-.106t-.252-.119t-.245-.13q-.122-.068-.24-.141q-.118-.074-.232-.152q-.115-.079-.226-.163t-.217-.174q-.107-.089-.21-.183q-.102-.093-.2-.192t-.192-.202q-.093-.103-.182-.21q-.088-.107-.172-.218q-.083-.112-.162-.227q-.078-.115-.151-.233t-.14-.24t-.129-.247q-.061-.125-.117-.252t-.105-.257t-.094-.262q-.043-.132-.081-.266q-.037-.134-.069-.27q-.031-.135-.056-.272t-.043-.275t-.031-.276M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
