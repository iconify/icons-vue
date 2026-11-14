<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upt9odo0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:active-calories" /></template>
<style>
.upt9odo0a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.383 20.128q-.777.429-1.636.651Q11.887 21 11 21q-.172 0-.343-.008t-.343-.026q-.171-.017-.341-.042t-.339-.059q-.168-.033-.335-.075t-.331-.091t-.326-.108t-.321-.124t-.314-.139t-.307-.155t-.299-.169t-.29-.184q-.143-.095-.281-.198q-.138-.102-.271-.211t-.26-.224t-.249-.237q-.121-.122-.237-.249t-.224-.26q-.109-.133-.211-.271q-.103-.138-.198-.281t-.184-.29t-.169-.299q-.081-.152-.155-.307q-.073-.155-.139-.314t-.124-.321t-.108-.326t-.091-.331t-.075-.335t-.059-.339t-.042-.341t-.026-.343Q4 14.172 4 14c0-3.5 2-5.5 3.5-7C8 9 9 10 10 10.5c0-3 .5-5.5 1-8c3.259 3.259 6.518 6.518 6.951 10.584m.831 2.763l-1.955 2.216a.564.564 0 0 0 .423.937a.833.833 0 0 1 .769 1.154l-.144.346a.272.272 0 0 0 .455.285l2.09-2.351A.561.561 0 0 0 20 17.5a.876.876 0 0 1-.823-1.175l.073-.2a.277.277 0 0 0-.468-.278");
}

</style>
