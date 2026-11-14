<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="othby7bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lightbulb-off" /></template>
<style>
.othby7bll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.595 17.5H9.5V15q-.207-.086-.408-.187q-.201-.1-.395-.214q-.193-.115-.378-.242t-.361-.267t-.342-.291t-.321-.314t-.298-.335t-.275-.356q-.131-.182-.249-.373t-.223-.39t-.195-.404t-.168-.416q-.076-.212-.138-.428q-.061-.216-.108-.435q-.046-.22-.078-.442q-.031-.223-.047-.447m2.419-5.531q.126-.101.257-.196t.267-.183t.275-.169t.284-.155q.143-.075.29-.142q.148-.066.298-.126t.303-.112t.309-.096t.312-.081q.158-.036.317-.065t.319-.049t.322-.034t.323-.017q.161-.005.323-.002q.161.004.323.015q.161.011.321.031q.161.019.32.046q.159.028.317.063t.314.078q.155.043.309.094q.153.05.304.109t.299.124t.292.138t.284.153t.277.167t.268.18t.259.194t.249.206t.238.218t.227.23t.216.241t.203.251q.166.216.313.445q.147.228.274.469t.235.49q.107.25.192.508t.15.522t.106.533t.06.54t.015.543t-.03.542t-.075.538t-.12.53t-.164.518t-.206.503t-.248.483t-.287.461q-.154.225-.325.436m-6.794 7.4h3.5M3.5 3.5l17 17");
}

</style>
