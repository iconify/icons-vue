<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nfxwups2m.css';
import '../../css/f/fhmjgx_zw.css';
import '../../css/g/g6wm6g5mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nfxwups2m"/><path class="fhmjgx_zw"/><path class="g6wm6g5mh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:card-exchange-01" /></template>
