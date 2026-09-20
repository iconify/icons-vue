<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/h9njkdbfq.css';
import '../../css/d/dqoud86nz.css';
import '../../css/k/ktpncgb0v.css';
import '../../css/a/arfwosbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="h9njkdbfq"/><path class="dqoud86nz"/><path class="ktpncgb0v"/><path class="arfwosbro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-transfer-linear" /></template>
