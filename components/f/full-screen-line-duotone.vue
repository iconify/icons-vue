<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i8utatbio.css';
import '../../css/x/x-1lf64uh.css';
import '../../css/u/un-u7xpwr.css';
import '../../css/r/ros5bvrws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i8utatbio"/><path class="x-1lf64uh"/><path class="un-u7xpwr"/><path class="ros5bvrws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:full-screen-line-duotone" /></template>
