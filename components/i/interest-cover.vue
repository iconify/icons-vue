<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdqiu6ylu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:interest-cover" /></template>
<style>
.qdqiu6ylu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.263 4.798l-8-3Q12.136 1.75 12 1.75t-.263.048l-8 3q-.108.04-.198.11t-.155.165t-.1.203q-.034.109-.034.224V11q0 7.902 8.478 11.199q.131.051.272.051t.272-.051Q20.75 18.902 20.75 11V5.5q0-.115-.034-.224t-.1-.203q-.065-.094-.155-.165q-.09-.07-.198-.11M8.75 6.5q2.5 0 2.5 2.5t-2.5 2.5T6.25 9t2.5-2.5m5.657 1.041q.045-.059.101-.107t.12-.085t.134-.06t.143-.033t.147-.004t.145.024q.071.02.138.053q.066.033.124.078q.118.091.192.221q.074.129.093.277t-.02.292t-.131.262l-6 7.75q-.045.059-.101.107t-.12.085t-.134.06q-.07.024-.143.033q-.074.009-.147.004q-.074-.005-.145-.024q-.072-.02-.138-.053t-.124-.078q-.118-.091-.192-.221q-.074-.129-.093-.277t.02-.292t.131-.262zM12.75 14.75q0-2.5 2.5-2.5t2.5 2.5t-2.5 2.5t-2.5-2.5");
}

</style>
