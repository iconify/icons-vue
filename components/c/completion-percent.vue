<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o969wlbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:completion-percent" /></template>
<style>
.o969wlbkn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12M9 6.75Q6.75 6.75 6.75 9T9 11.25T11.25 9T9 6.75m5.97 1.22l-7 7q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163l7-7q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094M12.75 15q0 2.25 2.25 2.25T17.25 15T15 12.75T12.75 15");
}

</style>
