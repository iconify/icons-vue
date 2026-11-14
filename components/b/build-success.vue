<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnobzneez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:build-success" /></template>
<style>
.dnobzneez {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 12q-.001 4.039 2.855 6.896T12 21.753t6.895-2.857T21.75 12q.001-4.039-2.855-6.896T12 2.247q-4.04 0-6.895 2.857Q2.249 7.961 2.25 12m8.726 2.166l4.971-5.423q.05-.054.11-.098q.059-.044.126-.075t.139-.049q.072-.017.145-.02q.074-.004.147.008q.073.011.143.036q.069.026.132.064t.118.088t.098.11q.044.059.075.126t.049.139q.017.072.02.145q.004.074-.008.147q-.011.073-.036.143q-.026.069-.064.132t-.088.118l-5.5 6l-.023.023q-.052.053-.113.094t-.13.069t-.141.043T11 16t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-3-3q-.106-.105-.163-.243t-.057-.287t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T8 11.5t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
