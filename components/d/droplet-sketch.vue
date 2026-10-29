<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g2mv2kb9g.css';
import '../../css/n/n97utxnno.css';
import '../../css/t/tqjxo4v_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g2mv2kb9g"/><path class="n97utxnno"/><path class="tqjxo4v_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:droplet-sketch" /></template>
