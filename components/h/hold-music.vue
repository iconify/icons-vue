<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9ueckkir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hold-music" /></template>
<style>
.d9ueckkir {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.75 2.75v3.877q-.436-.127-1-.127q-2.5 0-2.5 2.5t2.5 2.5t2.5-2.5V3.875l1.962.817q.068.029.14.043q.073.015.146.015q.074 0 .147-.014q.072-.014.141-.042t.129-.07q.062-.04.114-.093q.053-.052.094-.113t.069-.13q.058-.137.058-.286q0-.15-.056-.288q-.057-.138-.163-.243q-.105-.106-.243-.163l-3-1.25Q17.65 2 17.5 2q-.11 0-.216.032t-.198.092t-.162.146q-.071.085-.114.187l-.002.005q-.058.138-.058.288m-6.025 1.807Q10.243 2.75 8.5 2.75h-3q-2.75 0-2.75 2.75q0 6.311 4.72 11.03q4.719 4.72 11.03 4.72q2.75 0 2.75-2.75v-3q0-1.743-1.818-2.228l-3-.75l-.035-.007q-1.595-.32-2.521 1.069l-.633.949q-2.398-1.299-3.77-3.781l.943-.628q1.389-.926 1.069-2.521l-.007-.035z");
}

</style>
