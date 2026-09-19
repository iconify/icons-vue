<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/edbboo-hy.css';
import '../../css/q/q4hhm4b9u.css';
import '../../css/m/mfc7nxp-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="edbboo-hy"/><path class="q4hhm4b9u"/><path class="mfc7nxp-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:book" /></template>
