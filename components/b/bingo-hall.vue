<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uytrtbb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bingo-hall" /></template>
<style>
.uytrtbb8b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.731 8.879l6.75-5.162q1.519-1.161 3.038 0l6.75 5.162q.981.751.981 1.986v8.385q0 1.036-.732 1.768t-1.768.732H5.25q-1.036 0-1.768-.732T2.75 19.25v-8.385q0-1.235.981-1.986M15 9.75H9q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h4.708l-3.359 5.878q-.037.064-.06.134q-.024.07-.033.143q-.009.074-.004.147q.005.074.024.145q.02.072.053.138t.078.124q.045.059.101.107q.056.049.12.085t.134.06t.143.033t.147.004t.145-.024q.072-.02.138-.053t.124-.078t.107-.101t.085-.12l4-7q.099-.173.099-.372q0-.093-.023-.184t-.067-.173t-.108-.151t-.142-.12l-.038-.023Q15.199 9.75 15 9.75");
}

</style>
