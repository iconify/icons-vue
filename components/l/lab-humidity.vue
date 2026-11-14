<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shqcpsbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-humidity" /></template>
<style>
.shqcpsbjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.807 18.268q-.413.299-.867.529q-.455.231-.939.387q-.485.157-.988.237q-.504.079-1.013.079q-.16 0-.319-.008t-.318-.023t-.317-.039t-.314-.055q-.157-.031-.311-.07q-.155-.039-.308-.085t-.303-.1t-.297-.115t-.292-.129t-.285-.144t-.278-.157t-.269-.17q-.133-.089-.261-.184t-.252-.196q-.123-.102-.241-.209t-.231-.22t-.22-.231t-.209-.241q-.101-.124-.196-.252t-.184-.261q-.088-.132-.17-.269t-.157-.278t-.144-.285q-.068-.144-.129-.292q-.061-.147-.115-.297t-.1-.303t-.085-.308t-.07-.311t-.055-.314q-.023-.158-.039-.317q-.015-.159-.023-.318T3.5 13C3.5 9.5 7 6 10 2.5c2.926 3.414 6.328 6.828 6.494 10.242M14.75 21.25l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
