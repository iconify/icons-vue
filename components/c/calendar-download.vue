<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l4l1k5fea.css';
import '../../css/m/mht3mub3j.css';
import '../../css/a/auimte7dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l4l1k5fea"/><path class="mht3mub3j"/><path class="auimte7dn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:calendar-download" /></template>
