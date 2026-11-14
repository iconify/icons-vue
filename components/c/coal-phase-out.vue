<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb870j18f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:coal-phase-out" /></template>
<style>
.sb870j18f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m15.415 13.646L7.596 4.767q.25-.116.539-.183l4.982-1.15q1.021-.235 1.905.327l4.202 2.674q.97.618 1.132 1.756l.762 5.337q.177 1.237-.707 2.121zm-2.902 2.901l.073-.072L5.331 8.16L3.72 11.382q-.559 1.118 0 2.236l2.625 5.251q.692 1.382 2.237 1.381h6.193q1.036 0 1.768-.733");
}

</style>
