<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/iajx504bs.css';
import '../../css/q/qmvobh65p.css';
import '../../css/d/dj3sakoey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iajx504bs"/><path class="qmvobh65p"/><path class="dj3sakoey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:billiard-01" /></template>
