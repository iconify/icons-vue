<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si0nm0boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eye-check" /></template>
<style>
.si0nm0boe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.819 9.436Q4.443 3.75 9.75 3.75t7.931 5.686q.069.149.069.314t-.069.314Q15.057 15.75 9.75 15.75t-7.931-5.686q-.069-.149-.069-.314t.069-.314M6.5 9.75Q6.5 13 9.75 13T13 9.75T9.75 6.5T6.5 9.75m1.5 0q0 1.75 1.75 1.75t1.75-1.75T9.75 8T8 9.75m8.75 9.189l-1.47-1.469q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141T14 18t.014.146q.015.073.043.141t.069.13q.041.061.094.113l2 2q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l4.25-4.25q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 15t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094z");
}

</style>
