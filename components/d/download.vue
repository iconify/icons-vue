<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/r8ksu0s_d.css';
import '../../css/x/xx-_idbnk.css';
import '../../css/q/qokg58j2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="r8ksu0s_d"/><path class="xx-_idbnk"/><path class="qokg58j2s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:download" /></template>
