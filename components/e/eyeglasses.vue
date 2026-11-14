<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3n_qdb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eyeglasses" /></template>
<style>
.q3n_qdb6r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 8.25h7.25q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141T11 9v.042q.452-.104 1-.104t1 .104V9q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.75q0 4-4 4H17q-4 0-4-4v-1.128q-.356-.184-1-.184t-1 .184v1.128q0 4-4 4h-.75q-4 0-4-4V9q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T3 8.25");
}

</style>
