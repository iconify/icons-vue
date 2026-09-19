<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kwbel-b_g.css';
import '../../css/d/du9wco7gb.css';
import '../../css/y/y3it9jeju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kwbel-b_g"/><path class="du9wco7gb"/><path class="y3it9jeju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-lock" /></template>
