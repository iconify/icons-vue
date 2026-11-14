<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b133m2b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:alcohol-marker" /></template>
<style>
.b133m2b9w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.382 6.436l-1.498 1.497q-.543.543-.639 1.271q-.205-.027-.422-.027q-1.243 0-2.121.879l-4.773 4.773l-1.591 1.591q-.879.878-.879 2.121t.879 2.121q.878.879 2.121.879t2.121-.879l1.591-1.591l4.773-4.773q.879-.878.879-2.121q0-.217-.027-.422q.728-.096 1.27-.639l3.442-3.443q.848-.85.235-1.884t-1.768-.696l-2.638.776q-.55.162-.955.567M9.171 19.071q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163l-3.182-3.182q-.106-.105-.163-.243t-.057-.287t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094l3.182 3.182q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113");
}

</style>
