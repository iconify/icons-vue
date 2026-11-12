<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/s/s0urbhscb.css';
import '../../css/d/d-llkv2cb.css';
import '../../css/j/jhsistbnu.css';
import '../../css/p/phxo31wwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGRxqpmeZm" x1="256" x2="256" y1="506.7" y2="5.3" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset=".5" class="s0urbhscb"/><stop offset="1" class="d-llkv2cb"/></linearGradient><path fill="url(#SVGRxqpmeZm)" class="jhsistbnu"/><path class="phxo31wwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:databasement-light" /></template>
