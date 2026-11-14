<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fyu1ecb3c"/><path class="qh2g3mv5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:adopt-a-cat" /></template>
<style>
.fyu1ecb3c {
  d: path("M12.987 19.939Q12.495 20 12 20q-.184 0-.368-.008t-.367-.026q-.183-.017-.365-.042q-.183-.025-.363-.059q-.181-.033-.359-.075q-.179-.042-.355-.091q-.176-.05-.35-.108q-.173-.058-.343-.124t-.337-.139q-.166-.074-.328-.155q-.163-.081-.321-.169t-.311-.184q-.153-.095-.301-.198q-.148-.102-.29-.211t-.279-.224t-.266-.237t-.254-.249q-.124-.127-.241-.26t-.226-.271q-.11-.138-.212-.281t-.197-.29t-.181-.299q-.087-.152-.166-.307t-.149-.314q-.071-.159-.133-.321t-.115-.326t-.098-.331t-.081-.335t-.063-.339t-.045-.341t-.027-.343Q4.5 13.172 4.5 13V3.5L9 7h6l4.5-3.5V13q0 .189-.011.379M9.5 10.5h.01m4.99 0h.01M2.5 13L8 14m13.5-1.5l-4.919.894");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qh2g3mv5z {
  d: path("m18 21.5l-2.5-2.75A1.75 1.75 0 0 1 18 16.5a1.75 1.75 0 0 1 2.5 2.25Z");
}

</style>
