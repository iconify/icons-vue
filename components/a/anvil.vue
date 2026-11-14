<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0034ac4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:anvil" /></template>
<style>
.h0034ac4t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 3.75h-19q-.167 0-.318.071t-.258.199l-.006.007q-.082.101-.125.222q-.043.122-.043.251q0 .167.071.318t.199.258q.765.637 2.191 1.67Q7.5 9.128 7.5 11v3.25h-.75q-2.5 0-2.5 2.5v1q0 2.5 2.5 2.5h10.5q2.5 0 2.5-2.5v-1q0-2.5-2.5-2.5h-.75V11q0-2.75 2.5-2.75h2.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014M9 14.25V11q0-2.638-3.909-5.469l-.387-.281H20.75v1.5H19q-4 0-4 4.25v3.25z");
}

</style>
