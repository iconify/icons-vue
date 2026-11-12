<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6u19dbbl.css';
import '../../css/l/laqe9rlbp.css';
import '../../css/d/d9-01rbag.css';
import '../../css/o/ocwyltn_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGoc97GeEW" x1="433.4" x2="-10.6" y1="446.2" y2="73.6" gradientUnits="userSpaceOnUse"><stop offset="0" class="i6u19dbbl"/><stop offset=".63" class="laqe9rlbp"/><stop offset="1" class="d9-01rbag"/></linearGradient><path fill="url(#SVGoc97GeEW)" class="ocwyltn_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beszel" /></template>
