<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p-sf15bue.css';
import '../../css/f/f5r1qi0_e.css';
import '../../css/t/tb3176osp.css';
import '../../css/x/xk1n0w2qu.css';
import '../../css/x/x1fsbwbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p-sf15bue"/><path class="f5r1qi0_e"/><path class="tb3176osp"/><path class="xk1n0w2qu"/><path class="x1fsbwbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:benzene-ring-linear" /></template>
