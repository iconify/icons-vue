<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yghh3lr1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:active-calories" /></template>
<style>
.yghh3lr1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.544 20.985q-.164-.011-.328-.029q-.163-.018-.326-.045q-.163-.026-.324-.059q-.161-.034-.32-.075q-.16-.042-.317-.09q-.158-.049-.312-.105q-.155-.056-.307-.12q-.152-.063-.301-.133t-.295-.148t-.287-.161q-.141-.085-.279-.175q-.138-.091-.271-.188t-.261-.2t-.252-.212t-.242-.224t-.23-.235q-.113-.12-.22-.246q-.107-.125-.207-.255q-.101-.13-.196-.265q-.094-.135-.183-.274q-.088-.139-.169-.283t-.156-.29t-.143-.297q-.067-.15-.128-.303q-.06-.153-.114-.309q-.053-.156-.099-.314t-.084-.318q-.039-.161-.069-.322q-.031-.162-.054-.325q-.024-.163-.039-.327q-.016-.164-.023-.329Q4 14.165 4 14c0-3.5 2-5.5 3.5-7C8 9 9 10 10 10.5c0-3 .5-5.5 1-8c3.259 3.259 6.518 6.518 6.951 10.584m1.799 1.666L16 19h2.5l-1.25 3l4-4.5h-2.5Z");
}

</style>
