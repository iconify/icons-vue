<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="naskzbb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:industrial-sewing-machine" /></template>
<style>
.naskzbb7l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 15.25V6q0-2.75 2.75-2.75h12q2.75 0 2.75 2.75v3q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T21 9.75h-2.75V13q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T16.75 13V9.75h-7v5.5h10q1.036 0 1.768.732t.732 1.768v1q0 1.036-.732 1.768t-1.768.732H4.25q-2.5 0-2.5-2.5v-1q0-1.036.732-1.768t1.768-.732m13.25-7h2.75V6q0-1.25-1.25-1.25H7Q5.75 4.75 5.75 6v9.25h2.5V9q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T9 8.25z");
}

</style>
