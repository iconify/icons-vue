<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwifircge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:discount-bogo" /></template>
<style>
.qwifircge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 7.25V3H7L3.5 7.5l1.75 2.25M12.409 19h-1.175q-.171 0-.338-.039q-.167-.038-.321-.113t-.287-.184t-.238-.243l-2.334-3q-.076-.098-.135-.207q-.06-.11-.1-.227t-.061-.24t-.02-.247t.02-.247q.021-.122.061-.24t.1-.227t.135-.207l2.334-3q.105-.135.238-.243t.287-.184t.321-.113t.338-.039H20q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133q.028.068.049.139q.022.07.036.142q.015.073.022.146t.007.147v3.713M7 7.5h.01m3.74 7h.01M18 15v6m-3-3h6");
}

</style>
