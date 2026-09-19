<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/yz_qwb59l.css';
import '../../css/b/b8dvbqkre.css';
import '../../css/m/mpln52b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yz_qwb59l"/><path class="b8dvbqkre"/><path class="mpln52b5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bread-03" /></template>
