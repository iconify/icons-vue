<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1uixb0tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kendo-strike" /></template>
<style>
.a1uixb0tm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.524 13.415L19.97 2.97q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243L10.585 14.476q.038.06.071.12l1.374 1.374q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163l-.447-.447q-.17.245-.415.49l-3.535 3.535q-1.59 1.591-3.181 0t0-3.181l3.535-3.535q.245-.245.49-.415l-.447-.447q-.106-.105-.163-.243T6.75 12.5t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094l1.374 1.373q.06.034.12.072");
}

</style>
