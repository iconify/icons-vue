<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpvo5bnex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heavy-bag" /></template>
<style>
.lpvo5bnex {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 2h16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T20 3.5h-7.25v2.251q2.042.043 3.499 1.5q1.501 1.501 1.501 3.624v6.25q0 2.123-1.501 3.624t-3.624 1.501h-1.25q-2.123 0-3.624-1.501T6.25 17.125v-6.25q0-2.123 1.501-3.624q1.457-1.457 3.499-1.5V3.5H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q3.926 2 4 2");
}

</style>
