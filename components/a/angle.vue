<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl3het11f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:angle" /></template>
<style>
.vl3het11f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m10.403 14.473l9.136-9.452q.104-.107.159-.246q.054-.139.052-.288t-.062-.286q-.059-.137-.167-.24q-.053-.052-.115-.092t-.131-.067t-.141-.04q-.073-.013-.147-.012t-.146.017t-.14.045t-.128.072t-.112.095l-14.5 15q-.052.053-.092.115t-.067.131t-.04.141q-.013.073-.012.147t.017.146t.045.14t.072.128t.095.112q.105.102.24.156t.281.055H20q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 18.75h-7.782q-.211-2.427-1.815-4.277m-1.048 1.084q1.159 1.397 1.355 3.193H6.268z");
}

</style>
