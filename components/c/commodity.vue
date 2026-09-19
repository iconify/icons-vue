<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/ndycvloua.css';
import '../../css/n/n2rfvgnzc.css';
import '../../css/y/ybpq96i6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ndycvloua"/><path class="n2rfvgnzc"/><path class="ybpq96i6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:commodity" /></template>
