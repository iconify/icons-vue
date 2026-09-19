<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/ddghpn2-o.css';
import '../../css/m/mh06cqblr.css';
import '../../css/a/axf4zcygn.css';
import '../../css/v/vbqbujntv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="ddghpn2-o"/><path class="mh06cqblr"/><path class="axf4zcygn"/><path class="vbqbujntv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:image-down" /></template>
