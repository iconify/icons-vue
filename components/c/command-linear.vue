<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xmvx9bbmd.css';
import '../../css/w/w_9u0rbob.css';
import '../../css/c/czwys_6ab.css';
import '../../css/u/ulwx7ibev.css';
import '../../css/y/ypkivh3mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xmvx9bbmd"/><path class="w_9u0rbob"/><path class="czwys_6ab"/><path class="ulwx7ibev"/><path class="ypkivh3mh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:command-linear" /></template>
