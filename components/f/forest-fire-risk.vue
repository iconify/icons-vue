<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbwyl_6gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:forest-fire-risk" /></template>
<style>
.cbwyl_6gr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.34 20.076q-.377.226-.78.399q-.404.173-.827.29q-.424.117-.859.176T12 21q-.16 0-.319-.008t-.318-.023t-.317-.039t-.314-.055q-.157-.031-.311-.07q-.155-.039-.308-.085t-.303-.1t-.297-.115t-.292-.129t-.285-.144t-.278-.157t-.269-.17q-.133-.089-.261-.184t-.252-.196q-.123-.102-.241-.209t-.231-.22t-.22-.231t-.209-.241q-.101-.124-.196-.252t-.184-.261q-.088-.132-.17-.269t-.157-.278t-.144-.285q-.068-.144-.129-.292q-.061-.147-.115-.297t-.1-.303t-.085-.308t-.07-.311t-.055-.314q-.023-.158-.039-.317q-.015-.159-.023-.318T5.5 14.5c0-3.5 2-6 3-7.5c1 2 2 3 3 3.5c0-3-.5-5.5.5-8c2.094 2.932 5.241 5.513 6.208 9.507M18 14.75v3.5M18 21h.01");
}

</style>
