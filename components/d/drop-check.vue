<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blbgpqbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drop-check" /></template>
<style>
.blbgpqbzd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.619 19.795Q11.822 20 11 20q-.16 0-.319-.008t-.318-.023t-.317-.039t-.314-.055q-.157-.031-.311-.07q-.155-.039-.308-.085t-.303-.1t-.297-.115t-.292-.129t-.285-.144t-.278-.157t-.269-.17q-.133-.089-.261-.184t-.252-.196q-.123-.102-.241-.209t-.231-.22t-.22-.231t-.209-.241q-.101-.124-.196-.252t-.184-.261q-.088-.132-.17-.269t-.157-.278t-.144-.285q-.068-.144-.129-.292q-.061-.147-.115-.297t-.1-.303t-.085-.308t-.07-.311t-.055-.314q-.023-.158-.039-.317q-.015-.159-.023-.318T4.5 13.5c0-4 6.5-11 6.5-11s6.5 7 6.5 11q0 1.171-.408 2.268M14.75 18l2 2L21 15.75");
}

</style>
