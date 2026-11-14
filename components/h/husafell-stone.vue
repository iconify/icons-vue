<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a1fyo0b4m"/><path class="qq3xlubyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:husafell-stone" /></template>
<style>
.a1fyo0b4m {
  d: path("M14.289 20h-6.51q-.184 0-.364-.038q-.18-.039-.348-.113t-.316-.183q-.149-.108-.272-.245l-3.381-3.757q-.139-.154-.238-.336t-.152-.383t-.059-.408q-.005-.207.038-.41l1.194-5.572q.058-.27.197-.51q.138-.239.344-.424l4.079-3.672q.12-.108.257-.191q.137-.084.287-.142t.308-.087t.319-.029h5.103q.172 0 .342.034q.169.033.328.099t.303.162t.265.218l4.029 4.029q.222.221.353.506t.155.597l.37 4.81");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qq3xlubyx {
  d: path("m4 8l7 2.5l4.5-7M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
