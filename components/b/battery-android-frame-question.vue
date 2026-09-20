<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtvkm2lov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-frame-question" /></template>
<style>
.vtvkm2lov {
  fill: currentColor;
  d: path("M4.385 17q-1 0-1.693-.692T2 14.616V9.385q0-1 .692-1.693T4.385 7H15.66q-.212.227-.385.467T14.967 8H4.385q-.58 0-.982.403Q3 8.806 3 9.385v5.23q0 .58.403.982q.403.403.982.403H16.55q.023.279.123.532q.1.252.254.468zm15.491-.855q.182-.181.182-.453q0-.27-.182-.462q-.182-.191-.453-.191t-.453.19t-.181.463t.181.453t.453.182t.453-.182m-.884-2.478h.849q.038-.275.067-.518t.154-.449q.169-.267.368-.483t.41-.426q.426-.425.732-.906q.307-.481.307-1.114q0-.935-.697-1.555t-1.682-.62q-.815 0-1.479.435q-.663.435-.971 1.18l.775.333q.227-.5.672-.805t1.003-.306q.621 0 1.076.377t.455.973q0 .483-.279.878t-.617.708q-.275.256-.505.509t-.405.584q-.13.292-.182.578q-.05.285-.05.627m-14.608.949V9.385h10.582v5.23z");
}

</style>
