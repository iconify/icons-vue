<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/taogqpb9g.css';
import '../../css/t/tase98tfq.css';
import '../../css/f/frr67dw0i.css';
import '../../css/p/pob85mb3x.css';
import '../../css/a/avdzeya6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="taogqpb9g"/><path class="tase98tfq"/><path class="frr67dw0i"/><path class="pob85mb3x"/><path class="avdzeya6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-check-broken" /></template>
