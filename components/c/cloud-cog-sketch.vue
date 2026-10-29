<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yv00hmf2c.css';
import '../../css/y/yimpzkb5k.css';
import '../../css/u/uo7u3abxo.css';
import '../../css/p/pjuklj88t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k yv00hmf2c"/><path class="wm-k yimpzkb5k"/><path class="uo7u3abxo wm-k"/><path class="pjuklj88t wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-cog-sketch" /></template>
