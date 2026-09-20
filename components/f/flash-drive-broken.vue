<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fyr67fbfm.css';
import '../../css/j/jxhv6pb2q.css';
import '../../css/s/sa9yuacrk.css';
import '../../css/x/xp2bbwbqh.css';
import '../../css/b/baa-5bbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fyr67fbfm"/><path class="jxhv6pb2q"/><path class="sa9yuacrk"/><path class="xp2bbwbqh"/><path class="baa-5bbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flash-drive-broken" /></template>
