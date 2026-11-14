<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbpi4zbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:call-log-add" /></template>
<style>
.kbpi4zbic {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.226 15.688q-.256-.058-.51-.127t-.505-.149t-.498-.17t-.49-.191t-.482-.211t-.472-.231t-.463-.251q-.228-.131-.451-.271t-.44-.289t-.427-.307t-.414-.325t-.4-.342t-.385-.359t-.369-.374t-.354-.39q-.172-.199-.336-.404t-.32-.418t-.301-.431q-.147-.219-.284-.444t-.264-.455t-.245-.466q-.117-.235-.225-.475q-.107-.24-.205-.485q-.097-.244-.184-.493q-.087-.248-.163-.5t-.142-.506t-.121-.512t-.099-.517t-.077-.521q-.034-.261-.056-.523t-.033-.525T2.5 3.5q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036t.146-.022T4 2h3l1.5 4.5l-2.5 2q0 .197.019.392q.02.196.058.388q.038.193.095.381t.132.37t.168.355t.202.336t.234.316q.125.151.264.29t.29.264t.316.234q.163.109.336.202q.174.092.355.168q.182.075.37.132t.381.095t.388.058t.392.019l2-2.5l4.5 1.5v.666M18 15v6m-3-3h6");
}

</style>
