<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wwe3_g1bc"/><path class="gchnrzbjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:call-fire-service" /></template>
<style>
.gchnrzbjf {
  d: path("M15.25 14.5h2l.75 2.25l-1.25 1c.75 1.5 1.75 2.5 3.25 3.25l1-1.25h.5v2c-3.75 0-6.25-3.25-6.25-7.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wwe3_g1bc {
  d: path("M13.304 19.078Q12.191 19.5 11 19.5q-.16 0-.319-.008t-.318-.023t-.317-.039t-.314-.055q-.157-.031-.311-.07q-.155-.039-.308-.085t-.303-.1t-.297-.115t-.292-.129t-.285-.144t-.278-.157t-.269-.17q-.133-.089-.261-.184t-.252-.196q-.123-.102-.241-.209t-.231-.22t-.22-.231t-.209-.241q-.101-.124-.196-.252t-.184-.261q-.088-.132-.17-.269t-.157-.278t-.144-.285q-.068-.144-.129-.292q-.061-.147-.115-.297t-.1-.303t-.085-.308t-.07-.311t-.055-.314q-.023-.158-.039-.317q-.015-.159-.023-.318T4.5 13c0-3 1.5-5 3-6.5c.5 2 1.5 3 2.5 3.5c0-3 .25-5.5 1-7.5c3.155 2.704 5.904 5.409 6.415 9.212");
}

</style>
