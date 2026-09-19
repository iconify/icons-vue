<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sks-tacsx.css';
import '../../css/h/hsmtyjbkf.css';
import '../../css/l/ld5saecis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sks-tacsx"/><path class="hsmtyjbkf"/><path class="ld5saecis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bell-minus" /></template>
