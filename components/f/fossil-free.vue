<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ch_ck7n4n"/><path class="xk4ixxbvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fossil-free" /></template>
<style>
.ch_ck7n4n {
  d: path("M9.494 5.491C10.312 4.463 11.175 3.463 12 2.5C15 6 18.5 10 18.5 14q0 .26-.021.519m-2.953 4.942q-.392.253-.816.447q-.424.195-.872.327t-.909.198q-.462.067-.929.067q-.16 0-.319-.008t-.318-.023t-.317-.039t-.314-.055q-.157-.031-.311-.07q-.155-.039-.308-.085t-.303-.1t-.297-.115t-.292-.129t-.285-.144t-.278-.157t-.269-.17q-.133-.089-.261-.184t-.252-.196q-.123-.102-.241-.209t-.231-.22t-.22-.231t-.209-.241q-.101-.124-.196-.252t-.184-.261q-.088-.132-.17-.269t-.157-.278t-.144-.285q-.068-.144-.129-.292q-.061-.147-.115-.297t-.1-.303t-.085-.308t-.07-.311t-.055-.314q-.023-.158-.039-.317q-.015-.159-.023-.318T5.5 14c0-1.242.337-2.484.892-3.711");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xk4ixxbvk {
  d: path("M13.306 17.247q-.629.253-1.306.253m-8.5-14l17 17");
}

</style>
