<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdez2_b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:encryption-lock" /></template>
<style>
.zdez2_b7t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.749 10.751q-.685-.685-1.499-1.057V7q0-2.175-1.538-3.712Q14.175 1.75 12 1.75T8.288 3.288Q6.75 4.825 6.75 7v2.694q-.814.372-1.499 1.057q-1.501 1.501-1.501 3.624v2.75q0 2.123 1.501 3.624t3.624 1.501h6.25q2.123 0 3.624-1.501t1.501-3.624v-2.75q0-2.123-1.501-3.624M8.875 9.25q-.32 0-.625.034V7q0-3.75 3.75-3.75T15.75 7v2.284q-.305-.034-.625-.034zm3.125 3q2.25 0 2.25 2.25q0 1.837-1.5 2.174V18q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T11.25 18v-1.326q-1.5-.337-1.5-2.174q0-2.25 2.25-2.25");
}

</style>
