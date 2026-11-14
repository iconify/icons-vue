<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvzw8tpca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bass-guitar" /></template>
<style>
.lvzw8tpca {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.22 2.306L17.806 3.72q-.935.935-.457 1.87l-6.638 6.639q-.631-.337-1.529-.405q-2.444-.186-3.228 1.889q-1.465.006-2.647.994q-1.437 1.2-1.521 3.071t1.24 3.196q1.325 1.324 3.196 1.24t3.071-1.521q.988-1.182.994-2.647q2.075-.784 1.889-3.228q-.068-.898-.405-1.529l6.639-6.638q.935.478 1.87-.457l1.414-1.414q1.237-1.237 0-2.474t-2.474 0M7.53 18.47q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.105.106-.243.163T7 19.75t-.287-.057t-.243-.163l-2-2q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.25 17q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T5 16.25t.146.014q.073.015.141.043t.13.069q.061.041.113.094z");
}

</style>
