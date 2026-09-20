<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n04szjpnk.css';
import '../../css/h/hntgybcog.css';
import '../../css/y/y0pjkbb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGU06AidGb" class="n04szjpnk"/></defs><g class="hntgybcog"><use href="#SVGU06AidGb"/><use href="#SVGU06AidGb"/><path class="y0pjkbb8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:circle-half-circle" /></template>
